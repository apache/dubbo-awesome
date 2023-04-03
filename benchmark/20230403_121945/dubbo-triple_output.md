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
# Warmup Iteration   1: 1.460 ops/ms
# Warmup Iteration   2: 3.425 ops/ms
# Warmup Iteration   3: 7.065 ops/ms
Iteration   1: 7.652 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 7.980 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.876 ±(99.9%) 3.542 ops/ms [Average]
  (min, avg, max) = (7.652, 7.876, 7.995), stdev = 0.194
  CI (99.9%): [4.333, 11.418] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.174 ops/ms
# Warmup Iteration   2: 6.496 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 8.362 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.265 ±(99.9%) 2.417 ops/ms [Average]
  (min, avg, max) = (8.114, 8.265, 8.362), stdev = 0.132
  CI (99.9%): [5.848, 10.681] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.057 ops/ms
# Warmup Iteration   2: 6.183 ops/ms
# Warmup Iteration   3: 7.528 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 8.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.970 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (7.867, 7.970, 8.046), stdev = 0.092
  CI (99.9%): [6.283, 9.658] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.877 ops/ms
# Warmup Iteration   2: 5.668 ops/ms
# Warmup Iteration   3: 6.414 ops/ms
Iteration   1: 6.604 ops/ms
Iteration   2: 6.954 ops/ms
Iteration   3: 6.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.736 ±(99.9%) 3.469 ops/ms [Average]
  (min, avg, max) = (6.604, 6.736, 6.954), stdev = 0.190
  CI (99.9%): [3.266, 10.205] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.169 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.014 ms/op
Iteration   1: 3.979 ±(99.9%) 0.004 ms/op
Iteration   2: 3.967 ±(99.9%) 0.007 ms/op
Iteration   3: 4.094 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.013 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (3.967, 4.013, 4.094), stdev = 0.070
  CI (99.9%): [2.732, 5.295] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.739 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.406 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.005 ms/op
Iteration   1: 3.919 ±(99.9%) 0.008 ms/op
Iteration   2: 3.991 ±(99.9%) 0.008 ms/op
Iteration   3: 3.717 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.875 ±(99.9%) 2.591 ms/op [Average]
  (min, avg, max) = (3.717, 3.875, 3.991), stdev = 0.142
  CI (99.9%): [1.284, 6.467] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.668 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.344 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.010 ms/op
Iteration   1: 4.041 ±(99.9%) 0.006 ms/op
Iteration   2: 3.966 ±(99.9%) 0.011 ms/op
Iteration   3: 3.962 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.990 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (3.962, 3.990, 4.041), stdev = 0.045
  CI (99.9%): [3.177, 4.803] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.115 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.925 ±(99.9%) 0.010 ms/op
Iteration   1: 4.820 ±(99.9%) 0.010 ms/op
Iteration   2: 4.673 ±(99.9%) 0.006 ms/op
Iteration   3: 4.772 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.755 ±(99.9%) 1.372 ms/op [Average]
  (min, avg, max) = (4.673, 4.755, 4.820), stdev = 0.075
  CI (99.9%): [3.384, 6.127] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.002 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 5.059 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.417 ±(99.9%) 0.020 ms/op
Iteration   1: 4.149 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.513 ms/op
                 createUser·p0.99:   7.371 ms/op
                 createUser·p0.999:  18.990 ms/op
                 createUser·p0.9999: 26.158 ms/op
                 createUser·p1.00:   28.541 ms/op

Iteration   2: 3.949 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.862 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  26.116 ms/op
                 createUser·p0.9999: 28.276 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   3: 4.096 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  26.837 ms/op
                 createUser·p0.9999: 32.506 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236106
  mean =      4.063 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 237 
    [ 2.500,  5.000) = 218168 
    [ 5.000,  7.500) = 15031 
    [ 7.500, 10.000) = 1493 
    [10.000, 12.500) = 647 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     24.769 ms/op
     p(99.9900) =     31.974 ms/op
     p(99.9990) =     32.646 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.242 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.014 ms/op
Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.407 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 25.548 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.874 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  24.735 ms/op
                 existUser·p0.9999: 29.499 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.864 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 31.264 ms/op
                 existUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243934
  mean =      3.935 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 337 
    [ 2.500,  5.000) = 231217 
    [ 5.000,  7.500) = 9875 
    [ 7.500, 10.000) = 1822 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     18.188 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     32.360 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.126 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.991 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
Iteration   1: 4.293 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.071 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.973 ms/op
                 getUser·p0.95:   6.341 ms/op
                 getUser·p0.99:   10.011 ms/op
                 getUser·p0.999:  24.217 ms/op
                 getUser·p0.9999: 28.861 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   2: 4.153 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.220 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  15.922 ms/op
                 getUser·p0.9999: 28.387 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.376 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  11.043 ms/op
                 getUser·p0.9999: 28.769 ms/op
                 getUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231820
  mean =      4.140 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 215521 
    [ 5.000,  7.500) = 12021 
    [ 7.500, 10.000) = 3020 
    [10.000, 12.500) = 737 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.071 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.726 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     29.701 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.125 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.068 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.103 ±(99.9%) 0.020 ms/op
Iteration   1: 4.784 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  25.374 ms/op
                 listUser·p0.9999: 28.774 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 4.688 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  20.500 ms/op
                 listUser·p0.9999: 25.799 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.669 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.609 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   8.688 ms/op
                 listUser·p0.999:  17.089 ms/op
                 listUser·p0.9999: 18.388 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203633
  mean =      4.713 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 174400 
    [ 5.000,  7.500) = 23974 
    [ 7.500, 10.000) = 3599 
    [10.000, 12.500) = 865 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     19.595 ms/op
     p(99.9900) =     27.969 ms/op
     p(99.9990) =     30.602 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.876 ± 3.542  ops/ms
ClientPb.existUser                       thrpt       3   8.265 ± 2.417  ops/ms
ClientPb.getUser                         thrpt       3   7.970 ± 1.687  ops/ms
ClientPb.listUser                        thrpt       3   6.736 ± 3.469  ops/ms
ClientPb.createUser                       avgt       3   4.013 ± 1.281   ms/op
ClientPb.existUser                        avgt       3   3.875 ± 2.591   ms/op
ClientPb.getUser                          avgt       3   3.990 ± 0.813   ms/op
ClientPb.listUser                         avgt       3   4.755 ± 1.372   ms/op
ClientPb.createUser                     sample  236106   4.063 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.593           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.832           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.769           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.974           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.735           ms/op
ClientPb.existUser                      sample  243934   3.935 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.407           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.188           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.736           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.604           ms/op
ClientPb.getUser                        sample  231820   4.140 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.071           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.726           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.086           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.672           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  203633   4.713 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.048           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.595           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.969           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.769           ms/op
