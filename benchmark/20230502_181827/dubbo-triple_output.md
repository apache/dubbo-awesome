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
# Warmup Iteration   1: 2.519 ops/ms
# Warmup Iteration   2: 5.908 ops/ms
# Warmup Iteration   3: 8.978 ops/ms
Iteration   1: 9.673 ops/ms
Iteration   2: 10.117 ops/ms
Iteration   3: 9.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.897 ±(99.9%) 4.049 ops/ms [Average]
  (min, avg, max) = (9.673, 9.897, 10.117), stdev = 0.222
  CI (99.9%): [5.847, 13.946] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ops/ms
# Warmup Iteration   2: 9.390 ops/ms
# Warmup Iteration   3: 9.913 ops/ms
Iteration   1: 10.599 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 10.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.369 ±(99.9%) 3.699 ops/ms [Average]
  (min, avg, max) = (10.215, 10.369, 10.599), stdev = 0.203
  CI (99.9%): [6.670, 14.068] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 8.726 ops/ms
# Warmup Iteration   3: 9.305 ops/ms
Iteration   1: 9.790 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.030 ±(99.9%) 3.976 ops/ms [Average]
  (min, avg, max) = (9.790, 10.030, 10.215), stdev = 0.218
  CI (99.9%): [6.054, 14.005] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 8.344 ops/ms
Iteration   1: 8.491 ops/ms
Iteration   2: 8.602 ops/ms
Iteration   3: 8.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.584 ±(99.9%) 1.563 ops/ms [Average]
  (min, avg, max) = (8.491, 8.584, 8.659), stdev = 0.086
  CI (99.9%): [7.021, 10.147] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.820 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.006 ms/op
Iteration   1: 3.241 ±(99.9%) 0.006 ms/op
Iteration   2: 3.221 ±(99.9%) 0.009 ms/op
Iteration   3: 3.243 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.235 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (3.221, 3.235, 3.243), stdev = 0.012
  CI (99.9%): [3.008, 3.462] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.805 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.005 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
Iteration   2: 3.012 ±(99.9%) 0.008 ms/op
Iteration   3: 2.960 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.998 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (2.960, 2.998, 3.021), stdev = 0.033
  CI (99.9%): [2.399, 3.597] (assumes normal distribution)


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
# Warmup Iteration   1: 8.008 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.004 ms/op
Iteration   1: 3.146 ±(99.9%) 0.005 ms/op
Iteration   2: 3.334 ±(99.9%) 0.003 ms/op
Iteration   3: 3.087 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.189 ±(99.9%) 2.353 ms/op [Average]
  (min, avg, max) = (3.087, 3.189, 3.334), stdev = 0.129
  CI (99.9%): [0.836, 5.542] (assumes normal distribution)


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
# Warmup Iteration   1: 9.160 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.007 ms/op
Iteration   1: 3.720 ±(99.9%) 0.010 ms/op
Iteration   2: 3.726 ±(99.9%) 0.007 ms/op
Iteration   3: 3.705 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.717 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.705, 3.717, 3.726), stdev = 0.011
  CI (99.9%): [3.523, 3.911] (assumes normal distribution)


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
# Warmup Iteration   1: 8.222 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  11.390 ms/op
                 createUser·p0.9999: 19.425 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.260 ms/op
                 createUser·p0.95:   3.383 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  18.799 ms/op
                 createUser·p0.9999: 22.046 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  14.277 ms/op
                 createUser·p0.9999: 20.648 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302784
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23180 
    [ 2.500,  5.000) = 275329 
    [ 5.000,  7.500) = 3574 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     15.932 ms/op
     p(99.9900) =     21.126 ms/op
     p(99.9990) =     23.416 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 6.790 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.323 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  15.742 ms/op
                 existUser·p0.9999: 20.623 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.322 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 24.519 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.051 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.403 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.014 ms/op
                 existUser·p0.9999: 32.802 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304882
  mean =      3.148 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22272 
    [ 2.500,  5.000) = 277924 
    [ 5.000,  7.500) = 4153 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     30.983 ms/op
     p(99.9990) =     33.551 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 8.655 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.008 ms/op
Iteration   1: 3.245 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  15.646 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.407 ms/op
                 getUser·p0.999:  10.093 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.271 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.126 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 26.623 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296558
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12543 
    [ 2.500,  5.000) = 274513 
    [ 5.000,  7.500) = 8461 
    [ 7.500, 10.000) = 648 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     15.506 ms/op
     p(99.9900) =     25.221 ms/op
     p(99.9990) =     27.101 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.089 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.011 ms/op
Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.693 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.835 ms/op
                 listUser·p0.999:  14.114 ms/op
                 listUser·p0.9999: 21.736 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.783 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.060 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 15.265 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254292
  mean =      3.773 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 244738 
    [ 5.000,  7.500) = 7667 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     22.498 ms/op
     p(99.9990) =     23.247 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.897 ± 4.049  ops/ms
ClientPb.existUser                       thrpt       3  10.369 ± 3.699  ops/ms
ClientPb.getUser                         thrpt       3  10.030 ± 3.976  ops/ms
ClientPb.listUser                        thrpt       3   8.584 ± 1.563  ops/ms
ClientPb.createUser                       avgt       3   3.235 ± 0.227   ms/op
ClientPb.existUser                        avgt       3   2.998 ± 0.599   ms/op
ClientPb.getUser                          avgt       3   3.189 ± 2.353   ms/op
ClientPb.listUser                         avgt       3   3.717 ± 0.194   ms/op
ClientPb.createUser                     sample  302784   3.165 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.932           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.126           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.429           ms/op
ClientPb.existUser                      sample  304882   3.148 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.403           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.983           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.144           ms/op
ClientPb.getUser                        sample  296558   3.234 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.886           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.506           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.221           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  254292   3.773 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.783           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.498           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
