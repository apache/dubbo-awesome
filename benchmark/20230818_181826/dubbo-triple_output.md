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
# Warmup Iteration   1: 2.094 ops/ms
# Warmup Iteration   2: 5.677 ops/ms
# Warmup Iteration   3: 8.597 ops/ms
Iteration   1: 9.026 ops/ms
Iteration   2: 9.429 ops/ms
Iteration   3: 9.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.169 ±(99.9%) 4.121 ops/ms [Average]
  (min, avg, max) = (9.026, 9.169, 9.429), stdev = 0.226
  CI (99.9%): [5.048, 13.290] (assumes normal distribution)


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
# Warmup Iteration   1: 2.845 ops/ms
# Warmup Iteration   2: 8.572 ops/ms
# Warmup Iteration   3: 9.388 ops/ms
Iteration   1: 9.408 ops/ms
Iteration   2: 9.087 ops/ms
Iteration   3: 9.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.305 ±(99.9%) 3.448 ops/ms [Average]
  (min, avg, max) = (9.087, 9.305, 9.421), stdev = 0.189
  CI (99.9%): [5.857, 12.754] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.829 ops/ms
# Warmup Iteration   2: 8.498 ops/ms
# Warmup Iteration   3: 9.452 ops/ms
Iteration   1: 9.090 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.311 ±(99.9%) 4.080 ops/ms [Average]
  (min, avg, max) = (9.090, 9.311, 9.537), stdev = 0.224
  CI (99.9%): [5.231, 13.392] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.553 ops/ms
# Warmup Iteration   2: 6.889 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 7.686 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 7.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.820 ±(99.9%) 2.556 ops/ms [Average]
  (min, avg, max) = (7.686, 7.820, 7.966), stdev = 0.140
  CI (99.9%): [5.264, 10.375] (assumes normal distribution)


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
# Warmup Iteration   1: 10.710 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.007 ms/op
Iteration   1: 3.445 ±(99.9%) 0.006 ms/op
Iteration   2: 3.378 ±(99.9%) 0.008 ms/op
Iteration   3: 3.532 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.452 ±(99.9%) 1.412 ms/op [Average]
  (min, avg, max) = (3.378, 3.452, 3.532), stdev = 0.077
  CI (99.9%): [2.040, 4.863] (assumes normal distribution)


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
# Warmup Iteration   1: 7.850 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.676 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.003 ms/op
Iteration   1: 3.284 ±(99.9%) 0.010 ms/op
Iteration   2: 3.355 ±(99.9%) 0.005 ms/op
Iteration   3: 3.258 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.258, 3.299, 3.355), stdev = 0.050
  CI (99.9%): [2.382, 4.215] (assumes normal distribution)


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
# Warmup Iteration   1: 10.381 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.006 ms/op
Iteration   1: 3.617 ±(99.9%) 0.004 ms/op
Iteration   2: 3.577 ±(99.9%) 0.006 ms/op
Iteration   3: 3.537 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.577 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (3.537, 3.577, 3.617), stdev = 0.040
  CI (99.9%): [2.846, 4.308] (assumes normal distribution)


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
# Warmup Iteration   1: 11.112 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.006 ms/op
Iteration   1: 4.056 ±(99.9%) 0.009 ms/op
Iteration   2: 3.991 ±(99.9%) 0.013 ms/op
Iteration   3: 3.932 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.993 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.932, 3.993, 4.056), stdev = 0.062
  CI (99.9%): [2.862, 5.124] (assumes normal distribution)


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
# Warmup Iteration   1: 9.613 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.011 ms/op
Iteration   1: 3.477 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  20.246 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 3.415 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.939 ms/op
                 createUser·p0.999:  20.330 ms/op
                 createUser·p0.9999: 24.117 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 3.398 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  24.114 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279811
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10488 
    [ 2.500,  5.000) = 262552 
    [ 5.000,  7.500) = 5141 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     20.257 ms/op
     p(99.9900) =     26.772 ms/op
     p(99.9990) =     28.254 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 8.983 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.008 ms/op
Iteration   1: 3.282 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  11.546 ms/op
                 existUser·p0.9999: 21.980 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  20.831 ms/op
                 existUser·p0.9999: 23.798 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.387 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  18.594 ms/op
                 existUser·p0.9999: 31.722 ms/op
                 existUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285797
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8116 
    [ 2.500,  5.000) = 271040 
    [ 5.000,  7.500) = 5136 
    [ 7.500, 10.000) = 945 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     18.619 ms/op
     p(99.9900) =     30.079 ms/op
     p(99.9990) =     32.445 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 9.500 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.013 ms/op
Iteration   1: 3.561 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  19.923 ms/op
                 getUser·p0.9999: 21.955 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.642 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  21.561 ms/op
                 getUser·p0.9999: 30.765 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  13.591 ms/op
                 getUser·p0.9999: 29.579 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274270
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3238 
    [ 2.500,  5.000) = 259287 
    [ 5.000,  7.500) = 9713 
    [ 7.500, 10.000) = 1399 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.446 ms/op
     p(99.9900) =     29.730 ms/op
     p(99.9990) =     31.720 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 11.094 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.015 ms/op
Iteration   1: 4.153 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.751 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  20.083 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   3: 4.061 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236148
  mean =      4.068 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 226082 
    [ 5.000,  7.500) = 6772 
    [ 7.500, 10.000) = 2075 
    [10.000, 12.500) = 586 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      8.217 ms/op
     p(99.9000) =     17.624 ms/op
     p(99.9900) =     24.208 ms/op
     p(99.9990) =     25.566 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.169 ± 4.121  ops/ms
ClientPb.existUser                       thrpt       3   9.305 ± 3.448  ops/ms
ClientPb.getUser                         thrpt       3   9.311 ± 4.080  ops/ms
ClientPb.listUser                        thrpt       3   7.820 ± 2.556  ops/ms
ClientPb.createUser                       avgt       3   3.452 ± 1.412   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 0.916   ms/op
ClientPb.getUser                          avgt       3   3.577 ± 0.731   ms/op
ClientPb.listUser                         avgt       3   3.993 ± 1.131   ms/op
ClientPb.createUser                     sample  279811   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.221           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.431           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.772           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.196           ms/op
ClientPb.existUser                      sample  285797   3.359 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.256           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.619           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  274270   3.497 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.446           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.730           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.949           ms/op
ClientPb.listUser                       sample  236148   4.068 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.751           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.624           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.208           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.821           ms/op
