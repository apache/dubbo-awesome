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
# Warmup Iteration   1: 2.056 ops/ms
# Warmup Iteration   2: 4.908 ops/ms
# Warmup Iteration   3: 8.591 ops/ms
Iteration   1: 9.128 ops/ms
Iteration   2: 9.415 ops/ms
Iteration   3: 9.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.241 ±(99.9%) 2.793 ops/ms [Average]
  (min, avg, max) = (9.128, 9.241, 9.415), stdev = 0.153
  CI (99.9%): [6.448, 12.034] (assumes normal distribution)


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
# Warmup Iteration   1: 3.069 ops/ms
# Warmup Iteration   2: 8.595 ops/ms
# Warmup Iteration   3: 9.322 ops/ms
Iteration   1: 9.529 ops/ms
Iteration   2: 9.617 ops/ms
Iteration   3: 9.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.591 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (9.529, 9.591, 9.629), stdev = 0.055
  CI (99.9%): [8.596, 10.587] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.217 ops/ms
# Warmup Iteration   2: 8.596 ops/ms
# Warmup Iteration   3: 8.689 ops/ms
Iteration   1: 9.392 ops/ms
Iteration   2: 9.548 ops/ms
Iteration   3: 9.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.424 ±(99.9%) 2.029 ops/ms [Average]
  (min, avg, max) = (9.332, 9.424, 9.548), stdev = 0.111
  CI (99.9%): [7.395, 11.453] (assumes normal distribution)


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
# Warmup Iteration   1: 2.959 ops/ms
# Warmup Iteration   2: 7.180 ops/ms
# Warmup Iteration   3: 7.740 ops/ms
Iteration   1: 8.063 ops/ms
Iteration   2: 7.791 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.912 ±(99.9%) 2.528 ops/ms [Average]
  (min, avg, max) = (7.791, 7.912, 8.063), stdev = 0.139
  CI (99.9%): [5.384, 10.440] (assumes normal distribution)


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
# Warmup Iteration   1: 9.173 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.003 ms/op
Iteration   1: 3.512 ±(99.9%) 0.007 ms/op
Iteration   2: 3.485 ±(99.9%) 0.006 ms/op
Iteration   3: 3.380 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (3.380, 3.459, 3.512), stdev = 0.069
  CI (99.9%): [2.193, 4.725] (assumes normal distribution)


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
# Warmup Iteration   1: 9.045 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.007 ms/op
Iteration   1: 3.294 ±(99.9%) 0.008 ms/op
Iteration   2: 3.342 ±(99.9%) 0.004 ms/op
Iteration   3: 3.350 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.294, 3.329, 3.350), stdev = 0.030
  CI (99.9%): [2.773, 3.884] (assumes normal distribution)


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
# Warmup Iteration   1: 8.837 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.007 ms/op
Iteration   1: 3.432 ±(99.9%) 0.005 ms/op
Iteration   2: 3.453 ±(99.9%) 0.009 ms/op
Iteration   3: 3.554 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.480 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (3.432, 3.480, 3.554), stdev = 0.065
  CI (99.9%): [2.288, 4.672] (assumes normal distribution)


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
# Warmup Iteration   1: 10.722 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.008 ms/op
Iteration   1: 4.108 ±(99.9%) 0.006 ms/op
Iteration   2: 4.050 ±(99.9%) 0.010 ms/op
Iteration   3: 4.033 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.064 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (4.033, 4.064, 4.108), stdev = 0.039
  CI (99.9%): [3.346, 4.781] (assumes normal distribution)


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
# Warmup Iteration   1: 9.534 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.011 ms/op
Iteration   1: 3.362 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 23.084 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.396 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.550 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  20.105 ms/op
                 createUser·p0.9999: 24.216 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.492 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.323 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 33.872 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280886
  mean =      3.416 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12216 
    [ 2.500,  5.000) = 261886 
    [ 5.000,  7.500) = 5263 
    [ 7.500, 10.000) = 929 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     17.240 ms/op
     p(99.9900) =     32.667 ms/op
     p(99.9990) =     35.677 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 8.674 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
Iteration   1: 3.314 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  15.536 ms/op
                 existUser·p0.9999: 23.310 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  20.375 ms/op
                 existUser·p0.9999: 23.679 ms/op
                 existUser·p1.00:   26.083 ms/op

Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   6.457 ms/op
                 existUser·p0.999:  21.140 ms/op
                 existUser·p0.9999: 29.592 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285293
  mean =      3.361 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12069 
    [ 2.500,  5.000) = 265825 
    [ 5.000,  7.500) = 5909 
    [ 7.500, 10.000) = 1035 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     19.555 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.369 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.010 ms/op
Iteration   1: 3.540 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   5.156 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  17.577 ms/op
                 getUser·p0.9999: 20.151 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   2: 3.527 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   7.389 ms/op
                 getUser·p0.999:  19.005 ms/op
                 getUser·p0.9999: 22.346 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.469 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.589 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  18.088 ms/op
                 getUser·p0.9999: 24.732 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273439
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2248 
    [ 2.500,  5.000) = 261209 
    [ 5.000,  7.500) = 7754 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     23.680 ms/op
     p(99.9990) =     25.146 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 11.730 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.474 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.014 ms/op
Iteration   1: 4.236 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  22.052 ms/op
                 listUser·p0.9999: 24.999 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.157 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  16.840 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 4.050 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.671 ms/op
                 listUser·p0.999:  14.894 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231511
  mean =      4.146 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 216818 
    [ 5.000,  7.500) = 11446 
    [ 7.500, 10.000) = 2111 
    [10.000, 12.500) = 545 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     23.883 ms/op
     p(99.9990) =     26.636 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.241 ± 2.793  ops/ms
ClientPb.existUser                       thrpt       3   9.591 ± 0.996  ops/ms
ClientPb.getUser                         thrpt       3   9.424 ± 2.029  ops/ms
ClientPb.listUser                        thrpt       3   7.912 ± 2.528  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 1.266   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 0.556   ms/op
ClientPb.getUser                          avgt       3   3.480 ± 1.192   ms/op
ClientPb.listUser                         avgt       3   4.064 ± 0.717   ms/op
ClientPb.createUser                     sample  280886   3.416 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.438           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.240           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.667           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  285293   3.361 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.021           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.555           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.689           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  273439   3.512 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.247           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.990           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.887           ms/op
ClientPb.listUser                       sample  231511   4.146 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.395           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.249           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.351           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.883           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
