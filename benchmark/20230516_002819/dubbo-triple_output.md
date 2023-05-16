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
# Warmup Iteration   1: 2.266 ops/ms
# Warmup Iteration   2: 5.132 ops/ms
# Warmup Iteration   3: 8.634 ops/ms
Iteration   1: 9.382 ops/ms
Iteration   2: 9.378 ops/ms
Iteration   3: 9.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.463 ±(99.9%) 2.617 ops/ms [Average]
  (min, avg, max) = (9.378, 9.463, 9.629), stdev = 0.143
  CI (99.9%): [6.846, 12.080] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.634 ops/ms
# Warmup Iteration   2: 8.982 ops/ms
# Warmup Iteration   3: 9.764 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 9.441 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.790 ±(99.9%) 5.621 ops/ms [Average]
  (min, avg, max) = (9.441, 9.790, 10.023), stdev = 0.308
  CI (99.9%): [4.169, 15.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.114 ops/ms
# Warmup Iteration   2: 8.735 ops/ms
# Warmup Iteration   3: 9.161 ops/ms
Iteration   1: 9.711 ops/ms
Iteration   2: 9.618 ops/ms
Iteration   3: 9.387 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.572 ±(99.9%) 3.042 ops/ms [Average]
  (min, avg, max) = (9.387, 9.572, 9.711), stdev = 0.167
  CI (99.9%): [6.530, 12.615] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 7.041 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.077 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 8.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.145 ±(99.9%) 2.468 ops/ms [Average]
  (min, avg, max) = (8.057, 8.145, 8.301), stdev = 0.135
  CI (99.9%): [5.677, 10.613] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.108 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.009 ms/op
Iteration   1: 3.517 ±(99.9%) 0.005 ms/op
Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
Iteration   3: 3.260 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.391 ±(99.9%) 2.351 ms/op [Average]
  (min, avg, max) = (3.260, 3.391, 3.517), stdev = 0.129
  CI (99.9%): [1.040, 5.743] (assumes normal distribution)


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
# Warmup Iteration   1: 8.073 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.011 ms/op
Iteration   1: 3.228 ±(99.9%) 0.005 ms/op
Iteration   2: 3.198 ±(99.9%) 0.010 ms/op
Iteration   3: 3.228 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.218 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.198, 3.218, 3.228), stdev = 0.017
  CI (99.9%): [2.901, 3.535] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.728 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.004 ms/op
Iteration   1: 3.383 ±(99.9%) 0.005 ms/op
Iteration   2: 3.291 ±(99.9%) 0.010 ms/op
Iteration   3: 3.423 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.365 ±(99.9%) 1.235 ms/op [Average]
  (min, avg, max) = (3.291, 3.365, 3.423), stdev = 0.068
  CI (99.9%): [2.130, 4.600] (assumes normal distribution)


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
# Warmup Iteration   1: 10.713 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.007 ms/op
Iteration   1: 3.995 ±(99.9%) 0.009 ms/op
Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
Iteration   3: 3.880 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.933 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.880, 3.933, 3.995), stdev = 0.058
  CI (99.9%): [2.872, 4.994] (assumes normal distribution)


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
# Warmup Iteration   1: 10.099 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.011 ms/op
Iteration   1: 3.574 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   5.628 ms/op
                 createUser·p0.99:   7.307 ms/op
                 createUser·p0.999:  20.873 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   34.996 ms/op

Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.038 ms/op
                 createUser·p0.999:  22.610 ms/op
                 createUser·p0.9999: 27.948 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 25.940 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273414
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3854 
    [ 2.500,  5.000) = 258326 
    [ 5.000,  7.500) = 9896 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     33.107 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 8.420 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.010 ms/op
Iteration   1: 3.224 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.458 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  12.398 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.341 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  20.475 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.354 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.677 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  9.929 ms/op
                 existUser·p0.9999: 27.554 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290190
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8609 
    [ 2.500,  5.000) = 274883 
    [ 5.000,  7.500) = 5730 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     10.548 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     28.187 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 9.124 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.011 ms/op
Iteration   1: 3.385 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 27.805 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.015 ms/op
                 getUser·p0.999:  12.157 ms/op
                 getUser·p0.9999: 26.554 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.528 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.395 ms/op
                 getUser·p0.999:  21.147 ms/op
                 getUser·p0.9999: 40.558 ms/op
                 getUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282384
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 274681 
    [ 5.000, 10.000) = 7309 
    [10.000, 15.000) = 138 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 152 
    [25.000, 30.000) = 72 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     12.157 ms/op
     p(99.9900) =     38.260 ms/op
     p(99.9990) =     41.758 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


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
# Warmup Iteration   1: 10.057 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.014 ms/op
Iteration   1: 4.100 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   8.174 ms/op
                 listUser·p0.999:  21.263 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 3.823 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.201 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 18.109 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 3.900 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.105 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243733
  mean =      3.938 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 235541 
    [ 5.000,  7.500) = 5596 
    [ 7.500, 10.000) = 1730 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     23.220 ms/op
     p(99.9990) =     25.303 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.463 ± 2.617  ops/ms
ClientPb.existUser                       thrpt       3   9.790 ± 5.621  ops/ms
ClientPb.getUser                         thrpt       3   9.572 ± 3.042  ops/ms
ClientPb.listUser                        thrpt       3   8.145 ± 2.468  ops/ms
ClientPb.createUser                       avgt       3   3.391 ± 2.351   ms/op
ClientPb.existUser                        avgt       3   3.218 ± 0.317   ms/op
ClientPb.getUser                          avgt       3   3.365 ± 1.235   ms/op
ClientPb.listUser                         avgt       3   3.933 ± 1.061   ms/op
ClientPb.createUser                     sample  273414   3.508 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.034           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  290190   3.305 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.458           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.548           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.457           ms/op
ClientPb.getUser                        sample  282384   3.399 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.491           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.157           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.260           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.812           ms/op
ClientPb.listUser                       sample  243733   3.938 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.681           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.220           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.723           ms/op
