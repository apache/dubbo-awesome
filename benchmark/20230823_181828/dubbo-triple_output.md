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
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 6.072 ops/ms
# Warmup Iteration   3: 8.818 ops/ms
Iteration   1: 9.555 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 9.902 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.810 ±(99.9%) 4.075 ops/ms [Average]
  (min, avg, max) = (9.555, 9.810, 9.973), stdev = 0.223
  CI (99.9%): [5.735, 13.885] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ops/ms
# Warmup Iteration   2: 9.416 ops/ms
# Warmup Iteration   3: 9.795 ops/ms
Iteration   1: 10.006 ops/ms
Iteration   2: 9.862 ops/ms
Iteration   3: 9.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.943 ±(99.9%) 1.346 ops/ms [Average]
  (min, avg, max) = (9.862, 9.943, 10.006), stdev = 0.074
  CI (99.9%): [8.597, 11.290] (assumes normal distribution)


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
# Warmup Iteration   1: 3.383 ops/ms
# Warmup Iteration   2: 8.793 ops/ms
# Warmup Iteration   3: 9.268 ops/ms
Iteration   1: 9.916 ops/ms
Iteration   2: 10.152 ops/ms
Iteration   3: 9.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.942 ±(99.9%) 3.615 ops/ms [Average]
  (min, avg, max) = (9.759, 9.942, 10.152), stdev = 0.198
  CI (99.9%): [6.328, 13.557] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.977 ops/ms
# Warmup Iteration   2: 7.268 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.362 ±(99.9%) 2.088 ops/ms [Average]
  (min, avg, max) = (8.246, 8.362, 8.475), stdev = 0.114
  CI (99.9%): [6.275, 10.450] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.999 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.006 ms/op
Iteration   1: 3.302 ±(99.9%) 0.006 ms/op
Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
Iteration   3: 3.383 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.311 ±(99.9%) 1.233 ms/op [Average]
  (min, avg, max) = (3.249, 3.311, 3.383), stdev = 0.068
  CI (99.9%): [2.079, 4.544] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.344 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.005 ms/op
Iteration   1: 3.126 ±(99.9%) 0.003 ms/op
Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
Iteration   3: 3.152 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.162 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.126, 3.162, 3.207), stdev = 0.041
  CI (99.9%): [2.406, 3.917] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.134 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.003 ms/op
Iteration   1: 3.308 ±(99.9%) 0.003 ms/op
Iteration   2: 3.227 ±(99.9%) 0.003 ms/op
Iteration   3: 3.264 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.266 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (3.227, 3.266, 3.308), stdev = 0.040
  CI (99.9%): [2.532, 4.001] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.321 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.005 ms/op
Iteration   1: 3.769 ±(99.9%) 0.008 ms/op
Iteration   2: 3.759 ±(99.9%) 0.008 ms/op
Iteration   3: 3.839 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.789 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.759, 3.789, 3.839), stdev = 0.043
  CI (99.9%): [2.997, 4.581] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.475 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
Iteration   1: 3.189 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  19.268 ms/op
                 createUser·p0.9999: 21.200 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 29.800 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.653 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  16.118 ms/op
                 createUser·p0.9999: 19.641 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294245
  mean =      3.261 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24571 
    [ 2.500,  5.000) = 262663 
    [ 5.000,  7.500) = 5643 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     26.987 ms/op
     p(99.9990) =     30.150 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 6.488 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.161 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  14.562 ms/op
                 existUser·p0.9999: 20.509 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  12.948 ms/op
                 existUser·p0.9999: 25.103 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  11.512 ms/op
                 existUser·p0.9999: 21.535 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298699
  mean =      3.211 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25905 
    [ 2.500,  5.000) = 265600 
    [ 5.000,  7.500) = 6186 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     23.459 ms/op
     p(99.9990) =     25.430 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 8.325 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.011 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  15.830 ms/op
                 getUser·p0.9999: 18.785 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   2: 3.309 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  13.674 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.884 ms/op
                 getUser·p0.999:  11.607 ms/op
                 getUser·p0.9999: 20.611 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289127
  mean =      3.319 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18313 
    [ 2.500,  5.000) = 261384 
    [ 5.000,  7.500) = 8026 
    [ 7.500, 10.000) = 1041 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     11.528 ms/op
     p(99.9900) =     22.383 ms/op
     p(99.9990) =     23.319 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 8.089 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.013 ms/op
Iteration   1: 3.760 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  20.935 ms/op
                 listUser·p0.9999: 23.543 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 15.097 ms/op
                 listUser·p1.00:   15.172 ms/op

Iteration   3: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  13.042 ms/op
                 listUser·p0.9999: 19.885 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252197
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 243575 
    [ 5.000,  7.500) = 5421 
    [ 7.500, 10.000) = 2260 
    [10.000, 12.500) = 441 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     23.849 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.810 ± 4.075  ops/ms
ClientPb.existUser                       thrpt       3   9.943 ± 1.346  ops/ms
ClientPb.getUser                         thrpt       3   9.942 ± 3.615  ops/ms
ClientPb.listUser                        thrpt       3   8.362 ± 2.088  ops/ms
ClientPb.createUser                       avgt       3   3.311 ± 1.233   ms/op
ClientPb.existUser                        avgt       3   3.162 ± 0.756   ms/op
ClientPb.getUser                          avgt       3   3.266 ± 0.734   ms/op
ClientPb.listUser                         avgt       3   3.789 ± 0.792   ms/op
ClientPb.createUser                     sample  294245   3.261 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.251           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.482           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.987           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  298699   3.211 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.523           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.943           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.459           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.592           ms/op
ClientPb.getUser                        sample  289127   3.319 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.075           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.528           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.383           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.150           ms/op
ClientPb.listUser                       sample  252197   3.805 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.929           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.730           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.117           ms/op
