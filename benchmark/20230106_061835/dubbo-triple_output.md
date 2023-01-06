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
# Warmup Iteration   1: 1.636 ops/ms
# Warmup Iteration   2: 3.505 ops/ms
# Warmup Iteration   3: 6.853 ops/ms
Iteration   1: 7.390 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 7.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.628 ±(99.9%) 4.307 ops/ms [Average]
  (min, avg, max) = (7.390, 7.628, 7.862), stdev = 0.236
  CI (99.9%): [3.321, 11.936] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.158 ops/ms
# Warmup Iteration   2: 6.885 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.223 ops/ms
Iteration   2: 8.327 ops/ms
Iteration   3: 8.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.296 ±(99.9%) 1.163 ops/ms [Average]
  (min, avg, max) = (8.223, 8.296, 8.339), stdev = 0.064
  CI (99.9%): [7.133, 9.459] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.193 ops/ms
# Warmup Iteration   2: 6.323 ops/ms
# Warmup Iteration   3: 7.872 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 8.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.009 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (7.861, 8.009, 8.188), stdev = 0.166
  CI (99.9%): [4.985, 11.032] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.166 ops/ms
# Warmup Iteration   2: 5.281 ops/ms
# Warmup Iteration   3: 6.282 ops/ms
Iteration   1: 6.567 ops/ms
Iteration   2: 6.568 ops/ms
Iteration   3: 6.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.568 ±(99.9%) 0.013 ops/ms [Average]
  (min, avg, max) = (6.567, 6.568, 6.568), stdev = 0.001
  CI (99.9%): [6.555, 6.581] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.017 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.917 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.268 ±(99.9%) 0.006 ms/op
Iteration   1: 4.199 ±(99.9%) 0.005 ms/op
Iteration   2: 4.034 ±(99.9%) 0.007 ms/op
Iteration   3: 4.081 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.105 ±(99.9%) 1.555 ms/op [Average]
  (min, avg, max) = (4.034, 4.105, 4.199), stdev = 0.085
  CI (99.9%): [2.550, 5.660] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.794 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.005 ms/op
Iteration   1: 3.900 ±(99.9%) 0.006 ms/op
Iteration   2: 3.786 ±(99.9%) 0.009 ms/op
Iteration   3: 3.853 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.846 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (3.786, 3.846, 3.900), stdev = 0.057
  CI (99.9%): [2.803, 4.890] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.126 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.834 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.006 ms/op
Iteration   1: 3.983 ±(99.9%) 0.009 ms/op
Iteration   2: 3.978 ±(99.9%) 0.006 ms/op
Iteration   3: 3.944 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.968 ±(99.9%) 0.394 ms/op [Average]
  (min, avg, max) = (3.944, 3.968, 3.983), stdev = 0.022
  CI (99.9%): [3.575, 4.362] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.095 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.323 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.982 ±(99.9%) 0.006 ms/op
Iteration   1: 4.718 ±(99.9%) 0.008 ms/op
Iteration   2: 4.563 ±(99.9%) 0.013 ms/op
Iteration   3: 4.535 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.605 ±(99.9%) 1.800 ms/op [Average]
  (min, avg, max) = (4.535, 4.605, 4.718), stdev = 0.099
  CI (99.9%): [2.806, 6.405] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.114 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.283 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.311 ±(99.9%) 0.016 ms/op
Iteration   1: 4.033 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.806 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  25.035 ms/op
                 createUser·p0.9999: 27.003 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 4.049 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  21.440 ms/op
                 createUser·p0.9999: 29.069 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   3: 3.932 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  27.928 ms/op
                 createUser·p0.9999: 31.322 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239559
  mean =      4.004 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 248 
    [ 2.500,  5.000) = 222826 
    [ 5.000,  7.500) = 13556 
    [ 7.500, 10.000) = 1864 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     25.035 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.884 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.334 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.010 ms/op
Iteration   1: 3.840 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  24.415 ms/op
                 existUser·p0.9999: 39.082 ms/op
                 existUser·p1.00:   40.698 ms/op

Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   5.087 ms/op
                 existUser·p0.99:   7.094 ms/op
                 existUser·p0.999:  11.311 ms/op
                 existUser·p0.9999: 27.686 ms/op
                 existUser·p1.00:   29.655 ms/op

Iteration   3: 3.751 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.610 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  29.517 ms/op
                 existUser·p0.9999: 34.438 ms/op
                 existUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249310
  mean =      3.849 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 239661 
    [ 5.000, 10.000) = 9026 
    [10.000, 15.000) = 314 
    [15.000, 20.000) = 50 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 122 
    [30.000, 35.000) = 81 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     23.870 ms/op
     p(99.9900) =     35.600 ms/op
     p(99.9990) =     39.945 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.154 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
Iteration   1: 4.089 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   8.815 ms/op
                 getUser·p0.999:  14.840 ms/op
                 getUser·p0.9999: 26.089 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   2: 4.014 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.963 ms/op
                 getUser·p0.999:  25.494 ms/op
                 getUser·p0.9999: 27.428 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.424 ms/op
                 getUser·p0.999:  10.682 ms/op
                 getUser·p0.9999: 37.088 ms/op
                 getUser·p1.00:   40.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238779
  mean =      4.018 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 224081 
    [ 5.000, 10.000) = 13846 
    [10.000, 15.000) = 520 
    [15.000, 20.000) = 58 
    [20.000, 25.000) = 89 
    [25.000, 30.000) = 147 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     23.560 ms/op
     p(99.9900) =     35.668 ms/op
     p(99.9990) =     39.156 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.382 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.698 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.031 ±(99.9%) 0.018 ms/op
Iteration   1: 4.832 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.612 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  25.279 ms/op
                 listUser·p0.9999: 29.133 ms/op
                 listUser·p1.00:   29.557 ms/op

Iteration   2: 4.840 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  20.408 ms/op
                 listUser·p0.9999: 30.611 ms/op
                 listUser·p1.00:   33.292 ms/op

Iteration   3: 4.834 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  18.046 ms/op
                 listUser·p0.9999: 20.825 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198391
  mean =      4.835 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 155851 
    [ 5.000,  7.500) = 35386 
    [ 7.500, 10.000) = 5686 
    [10.000, 12.500) = 858 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     20.835 ms/op
     p(99.9900) =     29.464 ms/op
     p(99.9990) =     30.842 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.628 ± 4.307  ops/ms
ClientPb.existUser                       thrpt       3   8.296 ± 1.163  ops/ms
ClientPb.getUser                         thrpt       3   8.009 ± 3.023  ops/ms
ClientPb.listUser                        thrpt       3   6.568 ± 0.013  ops/ms
ClientPb.createUser                       avgt       3   4.105 ± 1.555   ms/op
ClientPb.existUser                        avgt       3   3.846 ± 1.043   ms/op
ClientPb.getUser                          avgt       3   3.968 ± 0.394   ms/op
ClientPb.listUser                         avgt       3   4.605 ± 1.800   ms/op
ClientPb.createUser                     sample  239559   4.004 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.897           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.035           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.409           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.456           ms/op
ClientPb.existUser                      sample  249310   3.849 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.108           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.309           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.870           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.600           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.698           ms/op
ClientPb.getUser                        sample  238779   4.018 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.992           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.333           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.938           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.560           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.668           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.042           ms/op
ClientPb.listUser                       sample  198391   4.835 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.835           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.464           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.292           ms/op
