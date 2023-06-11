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
# Warmup Iteration   1: 1.660 ops/ms
# Warmup Iteration   2: 4.309 ops/ms
# Warmup Iteration   3: 7.378 ops/ms
Iteration   1: 7.774 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 8.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.037 ±(99.9%) 4.374 ops/ms [Average]
  (min, avg, max) = (7.774, 8.037, 8.243), stdev = 0.240
  CI (99.9%): [3.663, 12.411] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 7.341 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.835 ops/ms
Iteration   3: 8.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.617 ±(99.9%) 4.936 ops/ms [Average]
  (min, avg, max) = (8.314, 8.617, 8.835), stdev = 0.271
  CI (99.9%): [3.681, 13.553] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.211 ops/ms
# Warmup Iteration   2: 6.982 ops/ms
# Warmup Iteration   3: 7.831 ops/ms
Iteration   1: 8.357 ops/ms
Iteration   2: 8.075 ops/ms
Iteration   3: 8.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.238 ±(99.9%) 2.658 ops/ms [Average]
  (min, avg, max) = (8.075, 8.238, 8.357), stdev = 0.146
  CI (99.9%): [5.580, 10.895] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 5.490 ops/ms
# Warmup Iteration   3: 6.493 ops/ms
Iteration   1: 6.789 ops/ms
Iteration   2: 7.131 ops/ms
Iteration   3: 6.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.963 ±(99.9%) 3.116 ops/ms [Average]
  (min, avg, max) = (6.789, 6.963, 7.131), stdev = 0.171
  CI (99.9%): [3.847, 10.080] (assumes normal distribution)


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
# Warmup Iteration   1: 13.006 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.003 ms/op
Iteration   1: 3.965 ±(99.9%) 0.005 ms/op
Iteration   2: 3.936 ±(99.9%) 0.009 ms/op
Iteration   3: 3.843 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.915 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.843, 3.915, 3.965), stdev = 0.064
  CI (99.9%): [2.747, 5.082] (assumes normal distribution)


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
# Warmup Iteration   1: 10.851 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.010 ms/op
Iteration   1: 3.644 ±(99.9%) 0.012 ms/op
Iteration   2: 3.746 ±(99.9%) 0.009 ms/op
Iteration   3: 3.849 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.746 ±(99.9%) 1.867 ms/op [Average]
  (min, avg, max) = (3.644, 3.746, 3.849), stdev = 0.102
  CI (99.9%): [1.879, 5.613] (assumes normal distribution)


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
# Warmup Iteration   1: 13.063 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.013 ms/op
Iteration   1: 4.014 ±(99.9%) 0.007 ms/op
Iteration   2: 3.864 ±(99.9%) 0.010 ms/op
Iteration   3: 3.855 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.911 ±(99.9%) 1.630 ms/op [Average]
  (min, avg, max) = (3.855, 3.911, 4.014), stdev = 0.089
  CI (99.9%): [2.281, 5.541] (assumes normal distribution)


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
# Warmup Iteration   1: 13.089 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.040 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.524 ±(99.9%) 0.010 ms/op
Iteration   1: 4.660 ±(99.9%) 0.010 ms/op
Iteration   2: 4.602 ±(99.9%) 0.006 ms/op
Iteration   3: 4.338 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.533 ±(99.9%) 3.130 ms/op [Average]
  (min, avg, max) = (4.338, 4.533, 4.660), stdev = 0.172
  CI (99.9%): [1.403, 7.664] (assumes normal distribution)


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
# Warmup Iteration   1: 13.234 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.018 ms/op
Iteration   1: 3.778 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  23.376 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 3.838 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  22.938 ms/op
                 createUser·p0.9999: 26.071 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 3.747 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 27.014 ms/op
                 createUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 253312
  mean =      3.787 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 422 
    [ 2.500,  5.000) = 246324 
    [ 5.000,  7.500) = 5376 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 9.897 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
Iteration   1: 3.663 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.827 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  22.097 ms/op
                 existUser·p0.9999: 25.299 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   2: 3.775 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 27.876 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 3.824 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.427 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  27.571 ms/op
                 existUser·p0.9999: 31.335 ms/op
                 existUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255739
  mean =      3.753 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 824 
    [ 2.500,  5.000) = 246945 
    [ 5.000,  7.500) = 6754 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     21.472 ms/op
     p(99.9900) =     29.767 ms/op
     p(99.9990) =     31.585 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 11.055 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.014 ms/op
Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   8.384 ms/op
                 getUser·p0.999:  22.955 ms/op
                 getUser·p0.9999: 28.150 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   2: 3.790 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  24.936 ms/op
                 getUser·p0.9999: 30.343 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   3: 3.977 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  13.303 ms/op
                 getUser·p0.9999: 29.524 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243182
  mean =      3.944 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 233636 
    [ 5.000,  7.500) = 7030 
    [ 7.500, 10.000) = 1634 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     22.938 ms/op
     p(99.9900) =     29.493 ms/op
     p(99.9990) =     30.755 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 12.830 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.237 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.016 ms/op
Iteration   1: 4.648 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  21.699 ms/op
                 listUser·p0.9999: 25.567 ms/op
                 listUser·p1.00:   27.329 ms/op

Iteration   2: 4.402 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  16.823 ms/op
                 listUser·p0.9999: 21.184 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 4.396 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   4.260 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 214256
  mean =      4.479 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 196114 
    [ 5.000,  7.500) = 14398 
    [ 7.500, 10.000) = 2872 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     19.144 ms/op
     p(99.9900) =     24.384 ms/op
     p(99.9990) =     26.257 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.037 ± 4.374  ops/ms
ClientPb.existUser                       thrpt       3   8.617 ± 4.936  ops/ms
ClientPb.getUser                         thrpt       3   8.238 ± 2.658  ops/ms
ClientPb.listUser                        thrpt       3   6.963 ± 3.116  ops/ms
ClientPb.createUser                       avgt       3   3.915 ± 1.168   ms/op
ClientPb.existUser                        avgt       3   3.746 ± 1.867   ms/op
ClientPb.getUser                          avgt       3   3.911 ± 1.630   ms/op
ClientPb.listUser                         avgt       3   4.533 ± 3.130   ms/op
ClientPb.createUser                     sample  253312   3.787 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.466           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.641           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.905           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.804           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.524           ms/op
ClientPb.existUser                      sample  255739   3.753 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.472           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.767           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  243182   3.944 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.938           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.493           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.802           ms/op
ClientPb.listUser                       sample  214256   4.479 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.253           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.192           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.144           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.384           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.329           ms/op
