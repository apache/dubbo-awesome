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
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 3.487 ops/ms
# Warmup Iteration   3: 7.029 ops/ms
Iteration   1: 7.276 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 7.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.647 ±(99.9%) 8.081 ops/ms [Average]
  (min, avg, max) = (7.276, 7.647, 8.137), stdev = 0.443
  CI (99.9%): [≈ 0, 15.728] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
# Warmup Iteration   2: 6.644 ops/ms
# Warmup Iteration   3: 8.121 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 8.728 ops/ms
Iteration   3: 8.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.536 ±(99.9%) 5.791 ops/ms [Average]
  (min, avg, max) = (8.170, 8.536, 8.728), stdev = 0.317
  CI (99.9%): [2.745, 14.327] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.503 ops/ms
# Warmup Iteration   2: 6.529 ops/ms
# Warmup Iteration   3: 8.011 ops/ms
Iteration   1: 8.104 ops/ms
Iteration   2: 8.118 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.104 ±(99.9%) 0.255 ops/ms [Average]
  (min, avg, max) = (8.090, 8.104, 8.118), stdev = 0.014
  CI (99.9%): [7.849, 8.359] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.365 ops/ms
# Warmup Iteration   2: 6.301 ops/ms
# Warmup Iteration   3: 6.806 ops/ms
Iteration   1: 7.129 ops/ms
Iteration   2: 6.843 ops/ms
Iteration   3: 6.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.898 ±(99.9%) 3.805 ops/ms [Average]
  (min, avg, max) = (6.722, 6.898, 7.129), stdev = 0.209
  CI (99.9%): [3.093, 10.703] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.943 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.011 ms/op
Iteration   1: 3.808 ±(99.9%) 0.017 ms/op
Iteration   2: 3.845 ±(99.9%) 0.016 ms/op
Iteration   3: 3.816 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.823 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.808, 3.823, 3.845), stdev = 0.020
  CI (99.9%): [3.464, 4.181] (assumes normal distribution)


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
# Warmup Iteration   1: 11.776 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.016 ms/op
Iteration   1: 3.917 ±(99.9%) 0.006 ms/op
Iteration   2: 3.762 ±(99.9%) 0.006 ms/op
Iteration   3: 3.634 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.771 ±(99.9%) 2.587 ms/op [Average]
  (min, avg, max) = (3.634, 3.771, 3.917), stdev = 0.142
  CI (99.9%): [1.184, 6.358] (assumes normal distribution)


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
# Warmup Iteration   1: 11.099 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.005 ms/op
Iteration   1: 3.989 ±(99.9%) 0.013 ms/op
Iteration   2: 3.740 ±(99.9%) 0.006 ms/op
Iteration   3: 3.742 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.824 ±(99.9%) 2.605 ms/op [Average]
  (min, avg, max) = (3.740, 3.824, 3.989), stdev = 0.143
  CI (99.9%): [1.219, 6.428] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.804 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.491 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.655 ±(99.9%) 0.017 ms/op
Iteration   1: 4.562 ±(99.9%) 0.016 ms/op
Iteration   2: 4.589 ±(99.9%) 0.015 ms/op
Iteration   3: 4.589 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.580 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (4.562, 4.580, 4.589), stdev = 0.016
  CI (99.9%): [4.295, 4.865] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.898 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 5.150 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.018 ms/op
Iteration   1: 4.097 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   7.292 ms/op
                 createUser·p0.999:  11.966 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  21.772 ms/op
                 createUser·p0.9999: 24.309 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  10.085 ms/op
                 createUser·p0.9999: 26.649 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242105
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 231842 
    [ 5.000,  7.500) = 8798 
    [ 7.500, 10.000) = 1075 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     25.749 ms/op
     p(99.9990) =     28.643 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.103 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.239 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.012 ms/op
Iteration   1: 3.937 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  20.595 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   2: 3.711 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  13.954 ms/op
                 existUser·p0.9999: 24.326 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.721 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  23.497 ms/op
                 existUser·p0.9999: 27.095 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253345
  mean =      3.787 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 244471 
    [ 5.000,  7.500) = 6848 
    [ 7.500, 10.000) = 1179 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     27.962 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.510 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.431 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.013 ms/op
Iteration   1: 3.968 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   6.087 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  20.591 ms/op
                 getUser·p0.9999: 24.148 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   6.562 ms/op
                 getUser·p0.999:  11.011 ms/op
                 getUser·p0.9999: 27.093 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 3.811 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  26.707 ms/op
                 getUser·p0.9999: 37.880 ms/op
                 getUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245013
  mean =      3.919 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 231823 
    [ 5.000,  7.500) = 10573 
    [ 7.500, 10.000) = 1938 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     37.323 ms/op
     p(99.9990) =     38.076 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 12.191 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 5.212 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.016 ms/op
Iteration   1: 4.622 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  22.405 ms/op
                 listUser·p0.9999: 31.985 ms/op
                 listUser·p1.00:   33.128 ms/op

Iteration   2: 4.528 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  16.761 ms/op
                 listUser·p0.9999: 20.183 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 4.441 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  15.943 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211734
  mean =      4.529 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 195709 
    [ 5.000,  7.500) = 12348 
    [ 7.500, 10.000) = 2501 
    [10.000, 12.500) = 576 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.530 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     30.403 ms/op
     p(99.9990) =     33.059 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.647 ± 8.081  ops/ms
ClientPb.existUser                       thrpt       3   8.536 ± 5.791  ops/ms
ClientPb.getUser                         thrpt       3   8.104 ± 0.255  ops/ms
ClientPb.listUser                        thrpt       3   6.898 ± 3.805  ops/ms
ClientPb.createUser                       avgt       3   3.823 ± 0.359   ms/op
ClientPb.existUser                        avgt       3   3.771 ± 2.587   ms/op
ClientPb.getUser                          avgt       3   3.824 ± 2.605   ms/op
ClientPb.listUser                         avgt       3   4.580 ± 0.285   ms/op
ClientPb.createUser                     sample  242105   3.964 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.491           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.846           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.749           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  253345   3.787 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.840           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.054           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.985           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.836           ms/op
ClientPb.getUser                        sample  245013   3.919 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.495           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.553           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.414           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.323           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.142           ms/op
ClientPb.listUser                       sample  211734   4.529 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.573           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.530           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.366           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.128           ms/op
