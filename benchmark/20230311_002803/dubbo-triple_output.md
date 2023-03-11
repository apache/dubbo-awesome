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
# Warmup Iteration   1: 2.430 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 8.741 ops/ms
Iteration   1: 9.116 ops/ms
Iteration   2: 9.146 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.217 ±(99.9%) 2.742 ops/ms [Average]
  (min, avg, max) = (9.116, 9.217, 9.390), stdev = 0.150
  CI (99.9%): [6.476, 11.959] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.387 ops/ms
# Warmup Iteration   2: 8.221 ops/ms
# Warmup Iteration   3: 9.309 ops/ms
Iteration   1: 9.619 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 9.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.771 ±(99.9%) 2.569 ops/ms [Average]
  (min, avg, max) = (9.619, 9.771, 9.897), stdev = 0.141
  CI (99.9%): [7.202, 12.340] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.877 ops/ms
# Warmup Iteration   2: 8.584 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.421 ops/ms
Iteration   2: 9.832 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.596 ±(99.9%) 3.875 ops/ms [Average]
  (min, avg, max) = (9.421, 9.596, 9.832), stdev = 0.212
  CI (99.9%): [5.721, 13.471] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 7.163 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.243 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.202 ±(99.9%) 1.278 ops/ms [Average]
  (min, avg, max) = (8.121, 8.202, 8.243), stdev = 0.070
  CI (99.9%): [6.925, 9.480] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.551 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.007 ms/op
Iteration   1: 3.385 ±(99.9%) 0.007 ms/op
Iteration   2: 3.307 ±(99.9%) 0.006 ms/op
Iteration   3: 3.431 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.374 ±(99.9%) 1.139 ms/op [Average]
  (min, avg, max) = (3.307, 3.374, 3.431), stdev = 0.062
  CI (99.9%): [2.236, 4.513] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.741 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.008 ms/op
Iteration   1: 3.287 ±(99.9%) 0.010 ms/op
Iteration   2: 3.405 ±(99.9%) 0.006 ms/op
Iteration   3: 3.306 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.333 ±(99.9%) 1.161 ms/op [Average]
  (min, avg, max) = (3.287, 3.333, 3.405), stdev = 0.064
  CI (99.9%): [2.172, 4.493] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.773 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.004 ms/op
Iteration   1: 3.403 ±(99.9%) 0.005 ms/op
Iteration   2: 3.308 ±(99.9%) 0.007 ms/op
Iteration   3: 3.313 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.341 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (3.308, 3.341, 3.403), stdev = 0.053
  CI (99.9%): [2.373, 4.310] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.777 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.006 ms/op
Iteration   1: 3.959 ±(99.9%) 0.012 ms/op
Iteration   2: 4.012 ±(99.9%) 0.007 ms/op
Iteration   3: 3.903 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.958 ±(99.9%) 0.991 ms/op [Average]
  (min, avg, max) = (3.903, 3.958, 4.012), stdev = 0.054
  CI (99.9%): [2.967, 4.949] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.529 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.011 ms/op
Iteration   1: 3.398 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  21.099 ms/op
                 createUser·p0.9999: 23.481 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.306 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  12.703 ms/op
                 createUser·p0.9999: 25.361 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   3: 3.373 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  20.642 ms/op
                 createUser·p0.9999: 27.875 ms/op
                 createUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285666
  mean =      3.358 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19556 
    [ 2.500,  5.000) = 260904 
    [ 5.000,  7.500) = 4391 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 148 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     20.764 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     28.752 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


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
# Warmup Iteration   1: 7.865 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
Iteration   1: 3.254 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  11.291 ms/op
                 existUser·p0.9999: 23.474 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.197 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 26.869 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  19.790 ms/op
                 existUser·p0.9999: 28.395 ms/op
                 existUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292745
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9062 
    [ 2.500,  5.000) = 279360 
    [ 5.000,  7.500) = 3518 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 9.315 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
Iteration   1: 3.451 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  21.932 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.147 ms/op

Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.468 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  10.441 ms/op
                 getUser·p0.9999: 29.348 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   3: 3.329 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   5.690 ms/op
                 getUser·p0.999:  22.519 ms/op
                 getUser·p0.9999: 30.081 ms/op
                 getUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282439
  mean =      3.397 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12680 
    [ 2.500,  5.000) = 260609 
    [ 5.000,  7.500) = 7859 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.264 ms/op
     p(99.9000) =     17.385 ms/op
     p(99.9900) =     29.582 ms/op
     p(99.9990) =     30.945 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 9.366 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
Iteration   1: 4.143 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.348 ms/op
                 listUser·p0.999:  18.554 ms/op
                 listUser·p0.9999: 27.698 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 3.884 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239440
  mean =      4.008 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 230709 
    [ 5.000,  7.500) = 5797 
    [ 7.500, 10.000) = 1914 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     25.963 ms/op
     p(99.9990) =     28.542 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.217 ± 2.742  ops/ms
ClientPb.existUser                       thrpt       3   9.771 ± 2.569  ops/ms
ClientPb.getUser                         thrpt       3   9.596 ± 3.875  ops/ms
ClientPb.listUser                        thrpt       3   8.202 ± 1.278  ops/ms
ClientPb.createUser                       avgt       3   3.374 ± 1.139   ms/op
ClientPb.existUser                        avgt       3   3.333 ± 1.161   ms/op
ClientPb.getUser                          avgt       3   3.341 ± 0.969   ms/op
ClientPb.listUser                         avgt       3   3.958 ± 0.991   ms/op
ClientPb.createUser                     sample  285666   3.358 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.026           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.764           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.230           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.934           ms/op
ClientPb.existUser                      sample  292745   3.276 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.262           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.272           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.557           ms/op
ClientPb.getUser                        sample  282439   3.397 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.468           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.264           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.385           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.571           ms/op
ClientPb.listUser                       sample  239440   4.008 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.372           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.056           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.963           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.705           ms/op
