# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 5.716 ops/ms
# Warmup Iteration   3: 8.233 ops/ms
Iteration   1: 9.344 ops/ms
Iteration   2: 9.339 ops/ms
Iteration   3: 9.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.349 ±(99.9%) 0.259 ops/ms [Average]
  (min, avg, max) = (9.339, 9.349, 9.365), stdev = 0.014
  CI (99.9%): [9.090, 9.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.935 ops/ms
# Warmup Iteration   2: 8.773 ops/ms
# Warmup Iteration   3: 9.457 ops/ms
Iteration   1: 9.923 ops/ms
Iteration   2: 9.260 ops/ms
Iteration   3: 9.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.566 ±(99.9%) 6.098 ops/ms [Average]
  (min, avg, max) = (9.260, 9.566, 9.923), stdev = 0.334
  CI (99.9%): [3.467, 15.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 8.405 ops/ms
# Warmup Iteration   3: 9.009 ops/ms
Iteration   1: 9.175 ops/ms
Iteration   2: 9.309 ops/ms
Iteration   3: 9.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.336 ±(99.9%) 3.224 ops/ms [Average]
  (min, avg, max) = (9.175, 9.336, 9.525), stdev = 0.177
  CI (99.9%): [6.112, 12.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.884 ops/ms
# Warmup Iteration   2: 7.244 ops/ms
# Warmup Iteration   3: 7.945 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.112 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (8.035, 8.112, 8.242), stdev = 0.113
  CI (99.9%): [6.048, 10.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.743 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.004 ms/op
Iteration   1: 3.383 ±(99.9%) 0.006 ms/op
Iteration   2: 3.446 ±(99.9%) 0.005 ms/op
Iteration   3: 3.305 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.378 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.305, 3.378, 3.446), stdev = 0.071
  CI (99.9%): [2.086, 4.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.004 ms/op
Iteration   1: 3.210 ±(99.9%) 0.005 ms/op
Iteration   2: 3.242 ±(99.9%) 0.006 ms/op
Iteration   3: 3.146 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.199 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (3.146, 3.199, 3.242), stdev = 0.049
  CI (99.9%): [2.308, 4.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.005 ms/op
Iteration   1: 3.575 ±(99.9%) 0.004 ms/op
Iteration   2: 3.326 ±(99.9%) 0.005 ms/op
Iteration   3: 3.446 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.449 ±(99.9%) 2.268 ms/op [Average]
  (min, avg, max) = (3.326, 3.449, 3.575), stdev = 0.124
  CI (99.9%): [1.181, 5.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.795 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.011 ms/op
Iteration   1: 4.015 ±(99.9%) 0.010 ms/op
Iteration   2: 4.050 ±(99.9%) 0.009 ms/op
Iteration   3: 3.966 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.010 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (3.966, 4.010, 4.050), stdev = 0.042
  CI (99.9%): [3.247, 4.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.763 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.866 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  17.904 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  21.658 ms/op
                 createUser·p0.9999: 25.582 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.381 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  15.293 ms/op
                 createUser·p0.9999: 20.605 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281781
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8594 
    [ 2.500,  5.000) = 266929 
    [ 5.000,  7.500) = 5422 
    [ 7.500, 10.000) = 451 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     16.883 ms/op
     p(99.9900) =     24.061 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.561 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.520 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 23.859 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.273 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  15.021 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  9.241 ms/op
                 existUser·p0.9999: 24.313 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296688
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9699 
    [ 2.500,  5.000) = 281937 
    [ 5.000,  7.500) = 4104 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     12.036 ms/op
     p(99.9900) =     23.866 ms/op
     p(99.9990) =     25.822 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.980 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.493 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.385 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  12.036 ms/op
                 getUser·p0.9999: 35.105 ms/op
                 getUser·p1.00:   37.093 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  21.597 ms/op
                 getUser·p0.9999: 25.878 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.394 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  20.900 ms/op
                 getUser·p0.9999: 27.118 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279500
  mean =      3.433 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5899 
    [ 2.500,  5.000) = 264597 
    [ 5.000,  7.500) = 7766 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.385 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     34.016 ms/op
     p(99.9990) =     35.705 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.575 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.014 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 23.301 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.359 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 16.553 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.355 ms/op
                 listUser·p0.999:  15.558 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239080
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 229736 
    [ 5.000,  7.500) = 7195 
    [ 7.500, 10.000) = 1227 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.200 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.744 ms/op
     p(99.9900) =     22.187 ms/op
     p(99.9990) =     23.908 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.349 ± 0.259  ops/ms
ClientPb.existUser                       thrpt       3   9.566 ± 6.098  ops/ms
ClientPb.getUser                         thrpt       3   9.336 ± 3.224  ops/ms
ClientPb.listUser                        thrpt       3   8.112 ± 2.064  ops/ms
ClientPb.createUser                       avgt       3   3.378 ± 1.292   ms/op
ClientPb.existUser                        avgt       3   3.199 ± 0.891   ms/op
ClientPb.getUser                          avgt       3   3.449 ± 2.268   ms/op
ClientPb.listUser                         avgt       3   4.010 ± 0.763   ms/op
ClientPb.createUser                     sample  281781   3.406 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.106           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.883           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.061           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.066           ms/op
ClientPb.existUser                      sample  296688   3.233 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.036           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.866           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.575           ms/op
ClientPb.getUser                        sample  279500   3.433 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.385           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.631           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.016           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.093           ms/op
ClientPb.listUser                       sample  239080   4.011 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.200           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.744           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.187           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
