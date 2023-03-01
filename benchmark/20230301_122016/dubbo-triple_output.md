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
# Warmup Iteration   1: 2.093 ops/ms
# Warmup Iteration   2: 5.517 ops/ms
# Warmup Iteration   3: 8.997 ops/ms
Iteration   1: 9.106 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.424 ±(99.9%) 5.096 ops/ms [Average]
  (min, avg, max) = (9.106, 9.424, 9.628), stdev = 0.279
  CI (99.9%): [4.328, 14.520] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 9.360 ops/ms
Iteration   1: 9.904 ops/ms
Iteration   2: 9.884 ops/ms
Iteration   3: 9.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.813 ±(99.9%) 2.585 ops/ms [Average]
  (min, avg, max) = (9.649, 9.813, 9.904), stdev = 0.142
  CI (99.9%): [7.228, 12.397] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 8.685 ops/ms
# Warmup Iteration   3: 9.121 ops/ms
Iteration   1: 9.098 ops/ms
Iteration   2: 9.682 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.378 ±(99.9%) 5.339 ops/ms [Average]
  (min, avg, max) = (9.098, 9.378, 9.682), stdev = 0.293
  CI (99.9%): [4.039, 14.717] (assumes normal distribution)


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
# Warmup Iteration   1: 2.989 ops/ms
# Warmup Iteration   2: 7.244 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 8.004 ops/ms
Iteration   2: 7.480 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.858 ±(99.9%) 6.016 ops/ms [Average]
  (min, avg, max) = (7.480, 7.858, 8.088), stdev = 0.330
  CI (99.9%): [1.842, 13.873] (assumes normal distribution)


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
# Warmup Iteration   1: 9.573 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.691 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
Iteration   1: 3.359 ±(99.9%) 0.010 ms/op
Iteration   2: 3.591 ±(99.9%) 0.004 ms/op
Iteration   3: 3.448 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.466 ±(99.9%) 2.134 ms/op [Average]
  (min, avg, max) = (3.359, 3.466, 3.591), stdev = 0.117
  CI (99.9%): [1.332, 5.600] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.504 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.381 ±(99.9%) 0.003 ms/op
Iteration   1: 3.233 ±(99.9%) 0.006 ms/op
Iteration   2: 3.320 ±(99.9%) 0.005 ms/op
Iteration   3: 3.318 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.290 ±(99.9%) 0.901 ms/op [Average]
  (min, avg, max) = (3.233, 3.290, 3.320), stdev = 0.049
  CI (99.9%): [2.389, 4.191] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.504 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.007 ms/op
Iteration   1: 3.497 ±(99.9%) 0.007 ms/op
Iteration   2: 3.462 ±(99.9%) 0.007 ms/op
Iteration   3: 3.338 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.432 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (3.338, 3.432, 3.497), stdev = 0.083
  CI (99.9%): [1.910, 4.954] (assumes normal distribution)


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
# Warmup Iteration   1: 11.040 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.288 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.009 ms/op
Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
Iteration   2: 3.975 ±(99.9%) 0.007 ms/op
Iteration   3: 3.949 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.939 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.893, 3.939, 3.975), stdev = 0.041
  CI (99.9%): [3.182, 4.696] (assumes normal distribution)


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
# Warmup Iteration   1: 10.790 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.017 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  20.457 ms/op
                 createUser·p0.9999: 23.101 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  22.577 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.598 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 28.187 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276548
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10493 
    [ 2.500,  5.000) = 259710 
    [ 5.000,  7.500) = 5322 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.927 ms/op
     p(99.9000) =     18.427 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     28.728 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 8.249 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.009 ms/op
Iteration   1: 3.315 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.859 ms/op
                 existUser·p0.999:  14.729 ms/op
                 existUser·p0.9999: 21.278 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.437 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 21.640 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.347 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  22.724 ms/op
                 existUser·p0.9999: 30.718 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285086
  mean =      3.365 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12141 
    [ 2.500,  5.000) = 267699 
    [ 5.000,  7.500) = 4365 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     28.524 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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
# Warmup Iteration   1: 10.255 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.010 ms/op
Iteration   1: 3.623 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.073 ms/op
                 getUser·p0.999:  20.176 ms/op
                 getUser·p0.9999: 26.848 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   2: 3.347 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  21.684 ms/op
                 getUser·p0.9999: 25.115 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.454 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  19.660 ms/op
                 getUser·p0.9999: 29.704 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276250
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8552 
    [ 2.500,  5.000) = 258834 
    [ 5.000,  7.500) = 7621 
    [ 7.500, 10.000) = 824 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     19.874 ms/op
     p(99.9900) =     29.078 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 12.071 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.013 ms/op
Iteration   1: 4.084 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  19.438 ms/op
                 listUser·p0.9999: 26.334 ms/op
                 listUser·p1.00:   27.460 ms/op

Iteration   2: 4.028 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.112 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.054 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 18.226 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235589
  mean =      4.074 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 226062 
    [ 5.000,  7.500) = 7203 
    [ 7.500, 10.000) = 1427 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     24.764 ms/op
     p(99.9990) =     27.425 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.424 ± 5.096  ops/ms
ClientPb.existUser                       thrpt       3   9.813 ± 2.585  ops/ms
ClientPb.getUser                         thrpt       3   9.378 ± 5.339  ops/ms
ClientPb.listUser                        thrpt       3   7.858 ± 6.016  ops/ms
ClientPb.createUser                       avgt       3   3.466 ± 2.134   ms/op
ClientPb.existUser                        avgt       3   3.290 ± 0.901   ms/op
ClientPb.getUser                          avgt       3   3.432 ± 1.522   ms/op
ClientPb.listUser                         avgt       3   3.939 ± 0.757   ms/op
ClientPb.createUser                     sample  276548   3.470 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.998           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.977           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.927           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.427           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.968           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  285086   3.365 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.384           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.524           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.933           ms/op
ClientPb.getUser                        sample  276250   3.471 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.001           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.358           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.267           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.874           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.078           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  235589   4.074 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.827           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.764           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.460           ms/op
