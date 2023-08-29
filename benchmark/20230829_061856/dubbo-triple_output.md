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
# Warmup Iteration   1: 2.602 ops/ms
# Warmup Iteration   2: 5.819 ops/ms
# Warmup Iteration   3: 9.263 ops/ms
Iteration   1: 9.822 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.667 ±(99.9%) 2.455 ops/ms [Average]
  (min, avg, max) = (9.579, 9.667, 9.822), stdev = 0.135
  CI (99.9%): [7.212, 12.122] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.973 ops/ms
# Warmup Iteration   2: 9.521 ops/ms
# Warmup Iteration   3: 10.037 ops/ms
Iteration   1: 10.034 ops/ms
Iteration   2: 9.916 ops/ms
Iteration   3: 9.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.908 ±(99.9%) 2.384 ops/ms [Average]
  (min, avg, max) = (9.773, 9.908, 10.034), stdev = 0.131
  CI (99.9%): [7.524, 12.291] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ops/ms
# Warmup Iteration   2: 9.290 ops/ms
# Warmup Iteration   3: 9.837 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 9.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.892 ±(99.9%) 2.812 ops/ms [Average]
  (min, avg, max) = (9.715, 9.892, 9.993), stdev = 0.154
  CI (99.9%): [7.080, 12.704] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 7.275 ops/ms
# Warmup Iteration   3: 8.458 ops/ms
Iteration   1: 8.222 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.414 ±(99.9%) 3.875 ops/ms [Average]
  (min, avg, max) = (8.222, 8.414, 8.642), stdev = 0.212
  CI (99.9%): [4.539, 12.289] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.360 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.004 ms/op
Iteration   1: 3.314 ±(99.9%) 0.005 ms/op
Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
Iteration   3: 3.213 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.237 ±(99.9%) 1.240 ms/op [Average]
  (min, avg, max) = (3.184, 3.237, 3.314), stdev = 0.068
  CI (99.9%): [1.998, 4.477] (assumes normal distribution)


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
# Warmup Iteration   1: 7.796 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.004 ms/op
Iteration   2: 3.172 ±(99.9%) 0.005 ms/op
Iteration   3: 3.133 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.120 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.056, 3.120, 3.172), stdev = 0.059
  CI (99.9%): [2.040, 4.201] (assumes normal distribution)


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
# Warmup Iteration   1: 8.115 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.634 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.004 ms/op
Iteration   1: 3.336 ±(99.9%) 0.004 ms/op
Iteration   2: 3.176 ±(99.9%) 0.002 ms/op
Iteration   3: 3.155 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.222 ±(99.9%) 1.808 ms/op [Average]
  (min, avg, max) = (3.155, 3.222, 3.336), stdev = 0.099
  CI (99.9%): [1.414, 5.031] (assumes normal distribution)


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
# Warmup Iteration   1: 8.913 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.918 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.007 ms/op
Iteration   1: 3.754 ±(99.9%) 0.007 ms/op
Iteration   2: 3.794 ±(99.9%) 0.006 ms/op
Iteration   3: 3.839 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.796 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (3.754, 3.796, 3.839), stdev = 0.042
  CI (99.9%): [3.021, 4.570] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.839 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.008 ms/op
Iteration   1: 3.244 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  11.297 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   6.010 ms/op
                 createUser·p0.999:  20.357 ms/op
                 createUser·p0.9999: 22.022 ms/op
                 createUser·p1.00:   22.938 ms/op

Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.493 ms/op
                 createUser·p0.999:  10.092 ms/op
                 createUser·p0.9999: 16.466 ms/op
                 createUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297977
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20033 
    [ 2.500,  5.000) = 270814 
    [ 5.000,  7.500) = 5558 
    [ 7.500, 10.000) = 1087 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.060 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.009 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.184 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 26.480 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.001 ms/op
                 existUser·p0.9999: 29.491 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   3: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  12.292 ms/op
                 existUser·p0.9999: 21.457 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304224
  mean =      3.154 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14995 
    [ 2.500,  5.000) = 282971 
    [ 5.000,  7.500) = 4992 
    [ 7.500, 10.000) = 863 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.757 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     27.863 ms/op
     p(99.9990) =     30.239 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 7.557 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.010 ms/op
Iteration   1: 3.361 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  18.765 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.118 ms/op
                 getUser·p0.9999: 22.919 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  10.525 ms/op
                 getUser·p0.9999: 21.928 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292311
  mean =      3.282 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15720 
    [ 2.500,  5.000) = 267171 
    [ 5.000,  7.500) = 7919 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 163 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     16.205 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.205 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 9.459 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.011 ms/op
Iteration   1: 3.842 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  15.905 ms/op
                 listUser·p0.9999: 23.670 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.749 ms/op
                 listUser·p0.999:  12.812 ms/op
                 listUser·p0.9999: 16.310 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.362 ms/op
                 listUser·p0.999:  14.121 ms/op
                 listUser·p0.9999: 15.024 ms/op
                 listUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253441
  mean =      3.786 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 244218 
    [ 5.000,  7.500) = 6395 
    [ 7.500, 10.000) = 2015 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     21.845 ms/op
     p(99.9990) =     23.984 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.667 ± 2.455  ops/ms
ClientPb.existUser                       thrpt       3   9.908 ± 2.384  ops/ms
ClientPb.getUser                         thrpt       3   9.892 ± 2.812  ops/ms
ClientPb.listUser                        thrpt       3   8.414 ± 3.875  ops/ms
ClientPb.createUser                       avgt       3   3.237 ± 1.240   ms/op
ClientPb.existUser                        avgt       3   3.120 ± 1.081   ms/op
ClientPb.getUser                          avgt       3   3.222 ± 1.808   ms/op
ClientPb.listUser                         avgt       3   3.796 ± 0.775   ms/op
ClientPb.createUser                     sample  297977   3.217 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.019           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.518           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.021           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.893           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.594           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.938           ms/op
ClientPb.existUser                      sample  304224   3.154 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.802           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.757           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.863           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  292311   3.282 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.768           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.446           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.560           ms/op
ClientPb.listUser                       sample  253441   3.786 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.094           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.845           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
