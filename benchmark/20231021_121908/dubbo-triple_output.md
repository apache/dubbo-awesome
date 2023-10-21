# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.282 ops/ms
# Warmup Iteration   2: 5.563 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 9.176 ops/ms
Iteration   2: 9.054 ops/ms
Iteration   3: 9.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.153 ±(99.9%) 1.642 ops/ms [Average]
  (min, avg, max) = (9.054, 9.153, 9.229), stdev = 0.090
  CI (99.9%): [7.511, 10.795] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 9.091 ops/ms
# Warmup Iteration   3: 9.725 ops/ms
Iteration   1: 9.628 ops/ms
Iteration   2: 9.729 ops/ms
Iteration   3: 9.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.681 ±(99.9%) 0.926 ops/ms [Average]
  (min, avg, max) = (9.628, 9.681, 9.729), stdev = 0.051
  CI (99.9%): [8.755, 10.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.858 ops/ms
# Warmup Iteration   2: 8.722 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 9.116 ops/ms
Iteration   2: 9.477 ops/ms
Iteration   3: 9.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.352 ±(99.9%) 3.725 ops/ms [Average]
  (min, avg, max) = (9.116, 9.352, 9.477), stdev = 0.204
  CI (99.9%): [5.627, 13.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.996 ops/ms
# Warmup Iteration   2: 7.407 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.974 ±(99.9%) 2.496 ops/ms [Average]
  (min, avg, max) = (7.866, 7.974, 8.128), stdev = 0.137
  CI (99.9%): [5.478, 10.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.469 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.004 ms/op
Iteration   1: 3.392 ±(99.9%) 0.006 ms/op
Iteration   2: 3.380 ±(99.9%) 0.008 ms/op
Iteration   3: 3.443 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.405 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.380, 3.405, 3.443), stdev = 0.034
  CI (99.9%): [2.789, 4.021] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.907 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.002 ms/op
Iteration   1: 3.290 ±(99.9%) 0.009 ms/op
Iteration   2: 3.314 ±(99.9%) 0.003 ms/op
Iteration   3: 3.279 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.294 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.279, 3.294, 3.314), stdev = 0.018
  CI (99.9%): [2.966, 3.623] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.870 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.004 ms/op
Iteration   1: 3.416 ±(99.9%) 0.004 ms/op
Iteration   2: 3.408 ±(99.9%) 0.002 ms/op
Iteration   3: 3.398 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.407 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.398, 3.407, 3.416), stdev = 0.009
  CI (99.9%): [3.239, 3.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.005 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.006 ms/op
Iteration   1: 4.034 ±(99.9%) 0.007 ms/op
Iteration   2: 4.070 ±(99.9%) 0.007 ms/op
Iteration   3: 3.885 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.996 ±(99.9%) 1.784 ms/op [Average]
  (min, avg, max) = (3.885, 3.996, 4.070), stdev = 0.098
  CI (99.9%): [2.212, 5.780] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.497 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
Iteration   1: 3.467 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  20.207 ms/op
                 createUser·p0.9999: 22.373 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.473 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.184 ms/op
                 createUser·p0.9999: 23.789 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   3: 3.443 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  18.298 ms/op
                 createUser·p0.9999: 24.391 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277232
  mean =      3.461 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9495 
    [ 2.500,  5.000) = 263105 
    [ 5.000,  7.500) = 3577 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 177 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     19.517 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.527 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.632 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.008 ms/op
Iteration   1: 3.311 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  12.212 ms/op
                 existUser·p0.9999: 26.301 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  21.758 ms/op
                 existUser·p0.9999: 25.165 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.503 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.352 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  14.223 ms/op
                 existUser·p0.9999: 27.193 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283216
  mean =      3.390 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7698 
    [ 2.500,  5.000) = 270947 
    [ 5.000,  7.500) = 3893 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     14.453 ms/op
     p(99.9900) =     26.400 ms/op
     p(99.9990) =     27.465 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.069 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.010 ms/op
Iteration   1: 3.580 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   7.225 ms/op
                 getUser·p0.999:  14.571 ms/op
                 getUser·p0.9999: 21.661 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 3.491 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  21.238 ms/op
                 getUser·p0.9999: 25.035 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.506 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  19.098 ms/op
                 getUser·p0.9999: 25.653 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272401
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5018 
    [ 2.500,  5.000) = 260344 
    [ 5.000,  7.500) = 5826 
    [ 7.500, 10.000) = 597 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 206 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     16.525 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     27.070 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.816 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.010 ms/op
Iteration   1: 4.186 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  19.680 ms/op
                 listUser·p0.9999: 22.076 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 4.114 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.087 ms/op
                 listUser·p0.999:  16.682 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   3: 4.121 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.426 ms/op
                 listUser·p0.9999: 16.519 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231648
  mean =      4.140 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 222890 
    [ 5.000,  7.500) = 6837 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 417 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.172 ms/op
     p(99.9000) =     16.789 ms/op
     p(99.9900) =     21.621 ms/op
     p(99.9990) =     23.026 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.153 ± 1.642  ops/ms
ClientPb.existUser                       thrpt       3   9.681 ± 0.926  ops/ms
ClientPb.getUser                         thrpt       3   9.352 ± 3.725  ops/ms
ClientPb.listUser                        thrpt       3   7.974 ± 2.496  ops/ms
ClientPb.createUser                       avgt       3   3.405 ± 0.616   ms/op
ClientPb.existUser                        avgt       3   3.294 ± 0.328   ms/op
ClientPb.getUser                          avgt       3   3.407 ± 0.168   ms/op
ClientPb.listUser                         avgt       3   3.996 ± 1.784   ms/op
ClientPb.createUser                     sample  277232   3.461 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.030           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.517           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.462           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.182           ms/op
ClientPb.existUser                      sample  283216   3.390 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.352           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.453           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.400           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.787           ms/op
ClientPb.getUser                        sample  272401   3.525 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.027           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.408           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.709           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.525           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.362           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.197           ms/op
ClientPb.listUser                       sample  231648   4.140 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.172           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.789           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.621           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.134           ms/op
