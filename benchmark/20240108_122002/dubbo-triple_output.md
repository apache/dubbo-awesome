# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.249 ops/ms
# Warmup Iteration   2: 11.991 ops/ms
# Warmup Iteration   3: 12.353 ops/ms
Iteration   1: 12.891 ops/ms
Iteration   2: 12.881 ops/ms
Iteration   3: 13.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.979 ±(99.9%) 2.939 ops/ms [Average]
  (min, avg, max) = (12.881, 12.979, 13.165), stdev = 0.161
  CI (99.9%): [10.040, 15.918] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.419 ops/ms
# Warmup Iteration   2: 13.092 ops/ms
# Warmup Iteration   3: 13.401 ops/ms
Iteration   1: 13.325 ops/ms
Iteration   2: 13.244 ops/ms
Iteration   3: 13.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.365 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (13.244, 13.365, 13.524), stdev = 0.144
  CI (99.9%): [10.735, 15.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.302 ops/ms
# Warmup Iteration   2: 12.191 ops/ms
# Warmup Iteration   3: 12.442 ops/ms
Iteration   1: 12.877 ops/ms
Iteration   2: 12.780 ops/ms
Iteration   3: 12.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.715 ±(99.9%) 3.700 ops/ms [Average]
  (min, avg, max) = (12.487, 12.715, 12.877), stdev = 0.203
  CI (99.9%): [9.015, 16.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.676 ops/ms
# Warmup Iteration   2: 10.415 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.612 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.529 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (10.477, 10.529, 10.612), stdev = 0.073
  CI (99.9%): [9.202, 11.856] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
Iteration   1: 2.548 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.565 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.535, 2.549, 2.565), stdev = 0.015
  CI (99.9%): [2.268, 2.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.004 ms/op
Iteration   1: 2.387 ±(99.9%) 0.004 ms/op
Iteration   2: 2.372 ±(99.9%) 0.005 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.401 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (2.372, 2.401, 2.444), stdev = 0.038
  CI (99.9%): [1.702, 3.099] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.101 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.005 ms/op
Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
Iteration   3: 2.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.562 ms/op [Average]
  (min, avg, max) = (2.487, 2.521, 2.547), stdev = 0.031
  CI (99.9%): [1.959, 3.083] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.782 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.948 ±(99.9%) 0.008 ms/op
Iteration   2: 2.950 ±(99.9%) 0.007 ms/op
Iteration   3: 2.955 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (2.948, 2.951, 2.955), stdev = 0.004
  CI (99.9%): [2.883, 3.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  12.058 ms/op
                 createUser·p0.9999: 15.504 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.887 ms/op
                 createUser·p0.999:  10.057 ms/op
                 createUser·p0.9999: 12.927 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.096 ms/op
                 createUser·p0.999:  9.605 ms/op
                 createUser·p0.9999: 11.682 ms/op
                 createUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383422
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 190959 
    [ 2.500,  3.750) = 187447 
    [ 3.750,  5.000) = 4131 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      9.676 ms/op
     p(99.9900) =     14.205 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.369 ±(99.9%) 0.005 ms/op
Iteration   1: 2.403 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   2.347 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  8.016 ms/op
                 existUser·p0.9999: 14.654 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.402 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   2.322 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  7.546 ms/op
                 existUser·p0.9999: 14.252 ms/op
                 existUser·p1.00:   15.548 ms/op

Iteration   3: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.355 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.211 ms/op
                 existUser·p0.99:   3.965 ms/op
                 existUser·p0.999:  6.491 ms/op
                 existUser·p0.9999: 11.952 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398733
  mean =      2.405 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 226926 
    [ 2.500,  3.750) = 163829 
    [ 3.750,  5.000) = 6416 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.343 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      7.096 ms/op
     p(99.9900) =     14.225 ms/op
     p(99.9990) =     14.964 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.887 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  5.698 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  10.379 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  9.230 ms/op
                 getUser·p0.9999: 11.021 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383120
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 191772 
    [ 2.500,  3.750) = 186682 
    [ 3.750,  5.000) = 3936 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      9.271 ms/op
     p(99.9900) =     13.687 ms/op
     p(99.9990) =     14.905 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.009 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 10.804 ms/op
                 listUser·p1.00:   11.174 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.279 ms/op
                 listUser·p0.9999: 10.509 ms/op
                 listUser·p1.00:   10.797 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.588 ms/op
                 listUser·p0.9999: 11.532 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317408
  mean =      3.021 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 90026 
    [ 2.500,  3.750) = 187454 
    [ 3.750,  5.000) = 32230 
    [ 5.000,  6.250) = 6024 
    [ 6.250,  7.500) = 832 
    [ 7.500,  8.750) = 255 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.496 ms/op
     p(99.9900) =     10.822 ms/op
     p(99.9990) =     11.910 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.979 ± 2.939  ops/ms
ClientPb.existUser                       thrpt       3  13.365 ± 2.629  ops/ms
ClientPb.getUser                         thrpt       3  12.715 ± 3.700  ops/ms
ClientPb.listUser                        thrpt       3  10.529 ± 1.327  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.281   ms/op
ClientPb.existUser                        avgt       3   2.401 ± 0.699   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.562   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.068   ms/op
ClientPb.createUser                     sample  383422   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.609           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.676           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.205           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.843           ms/op
ClientPb.existUser                      sample  398733   2.405 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.563           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.343           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.100           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.096           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.225           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.548           ms/op
ClientPb.getUser                        sample  383120   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.499           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.271           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.687           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.237           ms/op
ClientPb.listUser                       sample  317408   3.021 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.496           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.822           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.531           ms/op
