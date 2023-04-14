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
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 5.970 ops/ms
# Warmup Iteration   3: 8.681 ops/ms
Iteration   1: 9.204 ops/ms
Iteration   2: 9.606 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.327 ±(99.9%) 4.429 ops/ms [Average]
  (min, avg, max) = (9.169, 9.327, 9.606), stdev = 0.243
  CI (99.9%): [4.898, 13.755] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.958 ops/ms
# Warmup Iteration   2: 8.711 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 9.888 ops/ms
Iteration   2: 9.671 ops/ms
Iteration   3: 9.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.843 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (9.671, 9.843, 9.972), stdev = 0.155
  CI (99.9%): [7.016, 12.671] (assumes normal distribution)


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
# Warmup Iteration   1: 3.208 ops/ms
# Warmup Iteration   2: 8.871 ops/ms
# Warmup Iteration   3: 8.828 ops/ms
Iteration   1: 9.134 ops/ms
Iteration   2: 9.508 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.290 ±(99.9%) 3.547 ops/ms [Average]
  (min, avg, max) = (9.134, 9.290, 9.508), stdev = 0.194
  CI (99.9%): [5.743, 12.837] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.270 ops/ms
# Warmup Iteration   2: 7.071 ops/ms
# Warmup Iteration   3: 7.951 ops/ms
Iteration   1: 7.903 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.980 ±(99.9%) 2.518 ops/ms [Average]
  (min, avg, max) = (7.897, 7.980, 8.139), stdev = 0.138
  CI (99.9%): [5.461, 10.498] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.487 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.007 ms/op
Iteration   1: 3.398 ±(99.9%) 0.006 ms/op
Iteration   2: 3.327 ±(99.9%) 0.008 ms/op
Iteration   3: 3.484 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.403 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (3.327, 3.403, 3.484), stdev = 0.079
  CI (99.9%): [1.967, 4.840] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.921 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.007 ms/op
Iteration   1: 3.174 ±(99.9%) 0.011 ms/op
Iteration   2: 3.567 ±(99.9%) 0.005 ms/op
Iteration   3: 3.218 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.319 ±(99.9%) 3.928 ms/op [Average]
  (min, avg, max) = (3.174, 3.319, 3.567), stdev = 0.215
  CI (99.9%): [≈ 0, 7.247] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.518 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.009 ms/op
Iteration   1: 3.440 ±(99.9%) 0.009 ms/op
Iteration   2: 3.304 ±(99.9%) 0.012 ms/op
Iteration   3: 3.399 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.381 ±(99.9%) 1.270 ms/op [Average]
  (min, avg, max) = (3.304, 3.381, 3.440), stdev = 0.070
  CI (99.9%): [2.111, 4.652] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.837 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
Iteration   1: 4.057 ±(99.9%) 0.005 ms/op
Iteration   2: 3.914 ±(99.9%) 0.016 ms/op
Iteration   3: 3.974 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.982 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.914, 3.982, 4.057), stdev = 0.072
  CI (99.9%): [2.676, 5.287] (assumes normal distribution)


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
# Warmup Iteration   1: 9.318 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  18.490 ms/op
                 createUser·p0.9999: 21.571 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 3.434 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  21.851 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   3: 3.353 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 26.509 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282878
  mean =      3.393 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3511 
    [ 2.500,  5.000) = 272810 
    [ 5.000,  7.500) = 5560 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     18.321 ms/op
     p(99.9900) =     24.833 ms/op
     p(99.9990) =     26.509 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.752 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
Iteration   1: 3.335 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  9.519 ms/op
                 existUser·p0.9999: 21.601 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.507 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.154 ms/op
                 existUser·p0.999:  15.107 ms/op
                 existUser·p0.9999: 24.590 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.427 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.686 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  18.299 ms/op
                 existUser·p0.9999: 26.335 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287840
  mean =      3.334 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12451 
    [ 2.500,  5.000) = 270220 
    [ 5.000,  7.500) = 4195 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     11.400 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 8.118 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.010 ms/op
Iteration   1: 3.328 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  17.910 ms/op
                 getUser·p0.9999: 22.733 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.469 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.473 ms/op
                 getUser·p0.999:  22.247 ms/op
                 getUser·p0.9999: 24.797 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   3: 3.347 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  19.235 ms/op
                 getUser·p0.9999: 25.210 ms/op
                 getUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283753
  mean =      3.380 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5697 
    [ 2.500,  5.000) = 271706 
    [ 5.000,  7.500) = 5439 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     19.374 ms/op
     p(99.9900) =     24.355 ms/op
     p(99.9990) =     26.252 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 10.167 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.014 ms/op
Iteration   1: 4.077 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.712 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  18.698 ms/op
                 listUser·p0.9999: 30.605 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 3.960 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 20.074 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  13.873 ms/op
                 listUser·p0.9999: 15.153 ms/op
                 listUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240492
  mean =      3.991 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 230530 
    [ 5.000,  7.500) = 7679 
    [ 7.500, 10.000) = 1404 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     29.195 ms/op
     p(99.9990) =     30.991 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.327 ± 4.429  ops/ms
ClientPb.existUser                       thrpt       3   9.843 ± 2.828  ops/ms
ClientPb.getUser                         thrpt       3   9.290 ± 3.547  ops/ms
ClientPb.listUser                        thrpt       3   7.980 ± 2.518  ops/ms
ClientPb.createUser                       avgt       3   3.403 ± 1.436   ms/op
ClientPb.existUser                        avgt       3   3.319 ± 3.928   ms/op
ClientPb.getUser                          avgt       3   3.381 ± 1.270   ms/op
ClientPb.listUser                         avgt       3   3.982 ± 1.305   ms/op
ClientPb.createUser                     sample  282878   3.393 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.321           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.833           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  287840   3.334 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.491           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.579           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.400           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  283753   3.380 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.374           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.355           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.313           ms/op
ClientPb.listUser                       sample  240492   3.991 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.077           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.195           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.687           ms/op
