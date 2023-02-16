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
# Warmup Iteration   1: 2.244 ops/ms
# Warmup Iteration   2: 6.156 ops/ms
# Warmup Iteration   3: 8.806 ops/ms
Iteration   1: 9.507 ops/ms
Iteration   2: 9.316 ops/ms
Iteration   3: 9.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.358 ±(99.9%) 2.424 ops/ms [Average]
  (min, avg, max) = (9.251, 9.358, 9.507), stdev = 0.133
  CI (99.9%): [6.933, 11.782] (assumes normal distribution)


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
# Warmup Iteration   1: 3.273 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 9.666 ops/ms
Iteration   1: 10.111 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 9.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.965 ±(99.9%) 6.837 ops/ms [Average]
  (min, avg, max) = (9.540, 9.965, 10.245), stdev = 0.375
  CI (99.9%): [3.128, 16.802] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.361 ops/ms
# Warmup Iteration   2: 8.096 ops/ms
# Warmup Iteration   3: 9.131 ops/ms
Iteration   1: 9.299 ops/ms
Iteration   2: 9.412 ops/ms
Iteration   3: 9.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.443 ±(99.9%) 2.947 ops/ms [Average]
  (min, avg, max) = (9.299, 9.443, 9.618), stdev = 0.162
  CI (99.9%): [6.496, 12.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 7.448 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.293 ops/ms
Iteration   2: 7.865 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.082 ±(99.9%) 3.901 ops/ms [Average]
  (min, avg, max) = (7.865, 8.082, 8.293), stdev = 0.214
  CI (99.9%): [4.181, 11.983] (assumes normal distribution)


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
# Warmup Iteration   1: 9.595 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.003 ms/op
Iteration   1: 3.344 ±(99.9%) 0.005 ms/op
Iteration   2: 3.272 ±(99.9%) 0.010 ms/op
Iteration   3: 3.351 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.322 ±(99.9%) 0.791 ms/op [Average]
  (min, avg, max) = (3.272, 3.322, 3.351), stdev = 0.043
  CI (99.9%): [2.532, 4.113] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.425 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.010 ms/op
Iteration   1: 3.212 ±(99.9%) 0.007 ms/op
Iteration   2: 3.278 ±(99.9%) 0.005 ms/op
Iteration   3: 3.265 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.252 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.212, 3.252, 3.278), stdev = 0.035
  CI (99.9%): [2.611, 3.893] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.647 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.004 ms/op
Iteration   1: 3.433 ±(99.9%) 0.007 ms/op
Iteration   2: 3.346 ±(99.9%) 0.006 ms/op
Iteration   3: 3.390 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.390 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.346, 3.390, 3.433), stdev = 0.043
  CI (99.9%): [2.603, 4.176] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.946 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
Iteration   1: 3.925 ±(99.9%) 0.009 ms/op
Iteration   2: 4.083 ±(99.9%) 0.011 ms/op
Iteration   3: 3.954 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.987 ±(99.9%) 1.540 ms/op [Average]
  (min, avg, max) = (3.925, 3.987, 4.083), stdev = 0.084
  CI (99.9%): [2.447, 5.528] (assumes normal distribution)


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
# Warmup Iteration   1: 9.332 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
Iteration   1: 3.303 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  16.923 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  21.620 ms/op
                 createUser·p0.9999: 24.499 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  19.056 ms/op
                 createUser·p0.9999: 24.971 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279785
  mean =      3.428 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13822 
    [ 2.500,  5.000) = 258024 
    [ 5.000,  7.500) = 6847 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.553 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  19.397 ms/op
                 existUser·p0.9999: 27.995 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 3.289 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  15.981 ms/op
                 existUser·p0.9999: 23.382 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296575
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4777 
    [ 2.500,  5.000) = 287681 
    [ 5.000,  7.500) = 3378 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     18.181 ms/op
     p(99.9900) =     27.078 ms/op
     p(99.9990) =     28.747 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 9.550 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
Iteration   1: 3.405 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  18.673 ms/op
                 getUser·p0.9999: 21.745 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.575 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.427 ms/op
                 getUser·p0.999:  21.430 ms/op
                 getUser·p0.9999: 23.562 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.483 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  18.200 ms/op
                 getUser·p0.9999: 23.358 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275247
  mean =      3.486 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7340 
    [ 2.500,  5.000) = 260455 
    [ 5.000,  7.500) = 6490 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.177 ms/op
     p(99.9000) =     18.858 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.027 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 10.487 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.013 ms/op
Iteration   1: 3.932 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.075 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 21.880 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.730 ms/op
                 listUser·p0.9999: 19.845 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.045 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 19.566 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244231
  mean =      3.928 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 236377 
    [ 5.000,  7.500) = 5873 
    [ 7.500, 10.000) = 1210 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     15.674 ms/op
     p(99.9900) =     21.023 ms/op
     p(99.9990) =     22.410 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.358 ± 2.424  ops/ms
ClientPb.existUser                       thrpt       3   9.965 ± 6.837  ops/ms
ClientPb.getUser                         thrpt       3   9.443 ± 2.947  ops/ms
ClientPb.listUser                        thrpt       3   8.082 ± 3.901  ops/ms
ClientPb.createUser                       avgt       3   3.322 ± 0.791   ms/op
ClientPb.existUser                        avgt       3   3.252 ± 0.641   ms/op
ClientPb.getUser                          avgt       3   3.390 ± 0.787   ms/op
ClientPb.listUser                         avgt       3   3.987 ± 1.540   ms/op
ClientPb.createUser                     sample  279785   3.428 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.317           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.169           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.985           ms/op
ClientPb.existUser                      sample  296575   3.236 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.524           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.181           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.078           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  275247   3.486 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.177           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.858           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.298           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.379           ms/op
ClientPb.listUser                       sample  244231   3.928 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.075           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.674           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.023           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.610           ms/op
