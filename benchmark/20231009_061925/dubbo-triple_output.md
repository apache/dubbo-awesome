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
# Warmup Iteration   1: 2.012 ops/ms
# Warmup Iteration   2: 5.553 ops/ms
# Warmup Iteration   3: 8.364 ops/ms
Iteration   1: 8.842 ops/ms
Iteration   2: 8.853 ops/ms
Iteration   3: 8.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.856 ±(99.9%) 0.301 ops/ms [Average]
  (min, avg, max) = (8.842, 8.856, 8.874), stdev = 0.017
  CI (99.9%): [8.555, 9.157] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 7.873 ops/ms
# Warmup Iteration   3: 9.252 ops/ms
Iteration   1: 9.464 ops/ms
Iteration   2: 9.448 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.466 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (9.448, 9.466, 9.486), stdev = 0.019
  CI (99.9%): [9.113, 9.819] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.810 ops/ms
# Warmup Iteration   2: 7.707 ops/ms
# Warmup Iteration   3: 8.435 ops/ms
Iteration   1: 9.076 ops/ms
Iteration   2: 8.978 ops/ms
Iteration   3: 9.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.087 ±(99.9%) 2.096 ops/ms [Average]
  (min, avg, max) = (8.978, 9.087, 9.207), stdev = 0.115
  CI (99.9%): [6.991, 11.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.517 ops/ms
# Warmup Iteration   2: 6.955 ops/ms
# Warmup Iteration   3: 7.529 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 7.488 ops/ms
Iteration   3: 7.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.599 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (7.488, 7.599, 7.677), stdev = 0.098
  CI (99.9%): [5.805, 9.392] (assumes normal distribution)


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
# Warmup Iteration   1: 10.435 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.005 ms/op
Iteration   1: 3.584 ±(99.9%) 0.006 ms/op
Iteration   2: 3.570 ±(99.9%) 0.005 ms/op
Iteration   3: 3.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.571 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.560, 3.571, 3.584), stdev = 0.012
  CI (99.9%): [3.349, 3.793] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.158 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.855 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.004 ms/op
Iteration   1: 3.447 ±(99.9%) 0.005 ms/op
Iteration   2: 3.339 ±(99.9%) 0.007 ms/op
Iteration   3: 3.449 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.412 ±(99.9%) 1.149 ms/op [Average]
  (min, avg, max) = (3.339, 3.412, 3.449), stdev = 0.063
  CI (99.9%): [2.263, 4.561] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.508 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.003 ms/op
Iteration   1: 3.544 ±(99.9%) 0.004 ms/op
Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
Iteration   3: 3.521 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.540 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (3.521, 3.540, 3.555), stdev = 0.017
  CI (99.9%): [3.224, 3.856] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.246 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.265 ±(99.9%) 0.006 ms/op
Iteration   1: 4.353 ±(99.9%) 0.004 ms/op
Iteration   2: 4.255 ±(99.9%) 0.006 ms/op
Iteration   3: 4.290 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.299 ±(99.9%) 0.899 ms/op [Average]
  (min, avg, max) = (4.255, 4.299, 4.353), stdev = 0.049
  CI (99.9%): [3.400, 5.198] (assumes normal distribution)


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
# Warmup Iteration   1: 10.023 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.661 ±(99.9%) 0.013 ms/op
Iteration   1: 3.722 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   6.152 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  21.270 ms/op
                 createUser·p0.9999: 36.268 ms/op
                 createUser·p1.00:   39.518 ms/op

Iteration   2: 3.537 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  21.943 ms/op
                 createUser·p0.9999: 24.211 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.627 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   7.305 ms/op
                 createUser·p0.999:  24.212 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264566
  mean =      3.627 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3768 
    [ 2.500,  5.000) = 248290 
    [ 5.000,  7.500) = 9695 
    [ 7.500, 10.000) = 1935 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     21.955 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     36.372 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


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
# Warmup Iteration   1: 9.161 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
Iteration   1: 3.483 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  20.218 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 3.439 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  20.644 ms/op
                 existUser·p0.9999: 23.870 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.491 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  13.558 ms/op
                 existUser·p0.9999: 28.869 ms/op
                 existUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276415
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6633 
    [ 2.500,  5.000) = 260409 
    [ 5.000,  7.500) = 7330 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 380 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     18.227 ms/op
     p(99.9900) =     27.111 ms/op
     p(99.9990) =     29.998 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


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
# Warmup Iteration   1: 10.433 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.011 ms/op
Iteration   1: 3.600 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  21.135 ms/op
                 getUser·p0.9999: 23.629 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 3.643 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  14.893 ms/op
                 getUser·p0.9999: 25.549 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   3: 3.648 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.561 ms/op
                 getUser·p0.999:  23.953 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 264221
  mean =      3.630 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2264 
    [ 2.500,  5.000) = 252954 
    [ 5.000,  7.500) = 6841 
    [ 7.500, 10.000) = 1551 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     28.232 ms/op
     p(99.9990) =     30.783 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.158 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.014 ms/op
Iteration   1: 4.367 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.467 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   6.291 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  20.021 ms/op
                 listUser·p0.9999: 22.075 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 4.124 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  15.433 ms/op
                 listUser·p0.9999: 19.112 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.151 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  16.023 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227635
  mean =      4.211 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 215176 
    [ 5.000,  7.500) = 8606 
    [ 7.500, 10.000) = 2612 
    [10.000, 12.500) = 497 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.356 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     21.536 ms/op
     p(99.9990) =     24.278 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.856 ± 0.301  ops/ms
ClientPb.existUser                       thrpt       3   9.466 ± 0.353  ops/ms
ClientPb.getUser                         thrpt       3   9.087 ± 2.096  ops/ms
ClientPb.listUser                        thrpt       3   7.599 ± 1.794  ops/ms
ClientPb.createUser                       avgt       3   3.571 ± 0.222   ms/op
ClientPb.existUser                        avgt       3   3.412 ± 1.149   ms/op
ClientPb.getUser                          avgt       3   3.540 ± 0.316   ms/op
ClientPb.listUser                         avgt       3   4.299 ± 0.899   ms/op
ClientPb.createUser                     sample  264566   3.627 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.329           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.518           ms/op
ClientPb.existUser                      sample  276415   3.471 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.358           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.310           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.135           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.227           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.111           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.114           ms/op
ClientPb.getUser                        sample  264221   3.630 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.526           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.469           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.232           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  227635   4.211 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.467           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.536           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.722           ms/op
