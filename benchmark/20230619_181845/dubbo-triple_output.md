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
# Warmup Iteration   1: 2.479 ops/ms
# Warmup Iteration   2: 5.616 ops/ms
# Warmup Iteration   3: 9.248 ops/ms
Iteration   1: 9.713 ops/ms
Iteration   2: 9.829 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.780 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (9.713, 9.780, 9.829), stdev = 0.060
  CI (99.9%): [8.683, 10.876] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.277 ops/ms
# Warmup Iteration   2: 9.050 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.273 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.353 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (10.273, 10.353, 10.490), stdev = 0.119
  CI (99.9%): [8.177, 12.529] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.474 ops/ms
# Warmup Iteration   2: 8.317 ops/ms
# Warmup Iteration   3: 9.542 ops/ms
Iteration   1: 9.901 ops/ms
Iteration   2: 10.077 ops/ms
Iteration   3: 10.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.024 ±(99.9%) 1.947 ops/ms [Average]
  (min, avg, max) = (9.901, 10.024, 10.093), stdev = 0.107
  CI (99.9%): [8.076, 11.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ops/ms
# Warmup Iteration   2: 7.524 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 7.891 ops/ms
Iteration   2: 8.095 ops/ms
Iteration   3: 8.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.215 ±(99.9%) 7.245 ops/ms [Average]
  (min, avg, max) = (7.891, 8.215, 8.658), stdev = 0.397
  CI (99.9%): [0.970, 15.460] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.006 ms/op
Iteration   1: 3.298 ±(99.9%) 0.007 ms/op
Iteration   2: 3.162 ±(99.9%) 0.004 ms/op
Iteration   3: 3.320 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.260 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (3.162, 3.260, 3.320), stdev = 0.086
  CI (99.9%): [1.698, 4.822] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.080 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.004 ms/op
Iteration   1: 3.133 ±(99.9%) 0.003 ms/op
Iteration   2: 3.125 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.129 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (3.125, 3.129, 3.133), stdev = 0.004
  CI (99.9%): [3.056, 3.201] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.182 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.006 ms/op
Iteration   1: 3.288 ±(99.9%) 0.004 ms/op
Iteration   2: 3.109 ±(99.9%) 0.004 ms/op
Iteration   3: 3.139 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.179 ±(99.9%) 1.746 ms/op [Average]
  (min, avg, max) = (3.109, 3.179, 3.288), stdev = 0.096
  CI (99.9%): [1.432, 4.925] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.516 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.005 ms/op
Iteration   1: 3.753 ±(99.9%) 0.010 ms/op
Iteration   2: 3.782 ±(99.9%) 0.007 ms/op
Iteration   3: 3.777 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.753, 3.771, 3.782), stdev = 0.016
  CI (99.9%): [3.485, 4.056] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.524 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.009 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  19.768 ms/op
                 createUser·p0.9999: 25.532 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   2: 3.247 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  16.646 ms/op
                 createUser·p0.9999: 21.538 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.253 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  16.545 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295908
  mean =      3.240 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12515 
    [ 2.500,  5.000) = 277855 
    [ 5.000,  7.500) = 4526 
    [ 7.500, 10.000) = 494 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 128 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     16.567 ms/op
     p(99.9900) =     24.472 ms/op
     p(99.9990) =     25.921 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.778 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
Iteration   1: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.989 ms/op
                 existUser·p0.999:  8.792 ms/op
                 existUser·p0.9999: 21.390 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 29.219 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.936 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 22.486 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301789
  mean =      3.179 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25175 
    [ 2.500,  5.000) = 272384 
    [ 5.000,  7.500) = 3586 
    [ 7.500, 10.000) = 285 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     29.782 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


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
# Warmup Iteration   1: 8.952 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
Iteration   1: 3.347 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  19.413 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  10.583 ms/op
                 getUser·p0.9999: 22.908 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.055 ms/op
                 getUser·p0.999:  13.429 ms/op
                 getUser·p0.9999: 20.065 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291208
  mean =      3.294 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8211 
    [ 2.500,  5.000) = 273495 
    [ 5.000,  7.500) = 8600 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     17.065 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     24.579 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 9.108 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.012 ms/op
Iteration   1: 3.760 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  16.842 ms/op
                 listUser·p0.9999: 32.784 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 3.901 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 3.812 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.702 ms/op
                 listUser·p0.9999: 18.519 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250866
  mean =      3.823 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 242493 
    [ 5.000,  7.500) = 6416 
    [ 7.500, 10.000) = 1173 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 296 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.802 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     29.682 ms/op
     p(99.9990) =     33.161 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.780 ± 1.097  ops/ms
ClientPb.existUser                       thrpt       3  10.353 ± 2.176  ops/ms
ClientPb.getUser                         thrpt       3  10.024 ± 1.947  ops/ms
ClientPb.listUser                        thrpt       3   8.215 ± 7.245  ops/ms
ClientPb.createUser                       avgt       3   3.260 ± 1.562   ms/op
ClientPb.existUser                        avgt       3   3.129 ± 0.072   ms/op
ClientPb.getUser                          avgt       3   3.179 ± 1.746   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 0.286   ms/op
ClientPb.createUser                     sample  295908   3.240 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.171           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.567           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.472           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.116           ms/op
ClientPb.existUser                      sample  301789   3.179 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.918           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.731           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.048           ms/op
ClientPb.getUser                        sample  291208   3.294 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.259           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.065           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.167           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.642           ms/op
ClientPb.listUser                       sample  250866   3.823 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.391           ms/op
