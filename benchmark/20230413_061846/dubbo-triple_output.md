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
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 5.286 ops/ms
# Warmup Iteration   3: 8.735 ops/ms
Iteration   1: 8.878 ops/ms
Iteration   2: 9.501 ops/ms
Iteration   3: 9.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.269 ±(99.9%) 6.213 ops/ms [Average]
  (min, avg, max) = (8.878, 9.269, 9.501), stdev = 0.341
  CI (99.9%): [3.055, 15.482] (assumes normal distribution)


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
# Warmup Iteration   1: 3.547 ops/ms
# Warmup Iteration   2: 9.004 ops/ms
# Warmup Iteration   3: 9.508 ops/ms
Iteration   1: 9.741 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 9.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.694 ±(99.9%) 0.891 ops/ms [Average]
  (min, avg, max) = (9.644, 9.694, 9.741), stdev = 0.049
  CI (99.9%): [8.803, 10.584] (assumes normal distribution)


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
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 8.684 ops/ms
# Warmup Iteration   3: 9.173 ops/ms
Iteration   1: 9.317 ops/ms
Iteration   2: 9.560 ops/ms
Iteration   3: 9.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.371 ±(99.9%) 3.067 ops/ms [Average]
  (min, avg, max) = (9.237, 9.371, 9.560), stdev = 0.168
  CI (99.9%): [6.305, 12.438] (assumes normal distribution)


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
# Warmup Iteration   1: 2.649 ops/ms
# Warmup Iteration   2: 6.658 ops/ms
# Warmup Iteration   3: 7.814 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.025 ±(99.9%) 4.184 ops/ms [Average]
  (min, avg, max) = (7.791, 8.025, 8.250), stdev = 0.229
  CI (99.9%): [3.841, 12.209] (assumes normal distribution)


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
# Warmup Iteration   1: 8.794 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.005 ms/op
Iteration   1: 3.408 ±(99.9%) 0.006 ms/op
Iteration   2: 3.441 ±(99.9%) 0.005 ms/op
Iteration   3: 3.390 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.413 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.390, 3.413, 3.441), stdev = 0.026
  CI (99.9%): [2.937, 3.888] (assumes normal distribution)


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
# Warmup Iteration   1: 8.351 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.006 ms/op
Iteration   1: 3.286 ±(99.9%) 0.004 ms/op
Iteration   2: 3.422 ±(99.9%) 0.006 ms/op
Iteration   3: 3.450 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.386 ±(99.9%) 1.602 ms/op [Average]
  (min, avg, max) = (3.286, 3.386, 3.450), stdev = 0.088
  CI (99.9%): [1.784, 4.988] (assumes normal distribution)


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
# Warmup Iteration   1: 11.171 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.892 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.005 ms/op
Iteration   1: 3.504 ±(99.9%) 0.005 ms/op
Iteration   2: 3.484 ±(99.9%) 0.004 ms/op
Iteration   3: 3.581 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.523 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.484, 3.523, 3.581), stdev = 0.051
  CI (99.9%): [2.586, 4.460] (assumes normal distribution)


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
# Warmup Iteration   1: 11.722 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.009 ms/op
Iteration   1: 4.026 ±(99.9%) 0.014 ms/op
Iteration   2: 4.087 ±(99.9%) 0.009 ms/op
Iteration   3: 3.917 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.010 ±(99.9%) 1.571 ms/op [Average]
  (min, avg, max) = (3.917, 4.010, 4.087), stdev = 0.086
  CI (99.9%): [2.439, 5.581] (assumes normal distribution)


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
# Warmup Iteration   1: 10.586 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.015 ms/op
Iteration   1: 3.633 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.593 ms/op
                 createUser·p0.999:  24.019 ms/op
                 createUser·p0.9999: 26.267 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.910 ms/op
                 createUser·p0.999:  26.039 ms/op
                 createUser·p0.9999: 30.323 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 3.520 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  24.707 ms/op
                 createUser·p0.9999: 30.671 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271947
  mean =      3.529 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14186 
    [ 2.500,  5.000) = 250809 
    [ 5.000,  7.500) = 5743 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 104 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     30.107 ms/op
     p(99.9990) =     30.993 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 8.731 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.960 ms/op
                 existUser·p0.999:  19.581 ms/op
                 existUser·p0.9999: 23.326 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.479 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  12.157 ms/op
                 existUser·p0.9999: 25.618 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.553 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 28.377 ms/op
                 existUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275035
  mean =      3.488 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6677 
    [ 2.500,  5.000) = 262056 
    [ 5.000,  7.500) = 5190 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.994 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     27.935 ms/op
     p(99.9990) =     28.926 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 9.783 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.012 ms/op
Iteration   1: 3.509 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  21.573 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  23.790 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.048 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  18.753 ms/op
                 getUser·p0.9999: 28.705 ms/op
                 getUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277573
  mean =      3.455 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2414 
    [ 2.500,  5.000) = 266606 
    [ 5.000,  7.500) = 7599 
    [ 7.500, 10.000) = 630 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.341 ms/op
     p(99.9000) =     19.248 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.390 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 11.591 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.739 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.017 ms/op
Iteration   1: 4.189 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  21.004 ms/op
                 listUser·p0.9999: 24.478 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  21.135 ms/op
                 listUser·p0.9999: 29.040 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   3: 4.090 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  15.601 ms/op
                 listUser·p0.9999: 21.010 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232083
  mean =      4.131 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 222744 
    [ 5.000,  7.500) = 6190 
    [ 7.500, 10.000) = 2115 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.269 ± 6.213  ops/ms
ClientPb.existUser                       thrpt       3   9.694 ± 0.891  ops/ms
ClientPb.getUser                         thrpt       3   9.371 ± 3.067  ops/ms
ClientPb.listUser                        thrpt       3   8.025 ± 4.184  ops/ms
ClientPb.createUser                       avgt       3   3.413 ± 0.475   ms/op
ClientPb.existUser                        avgt       3   3.386 ± 1.602   ms/op
ClientPb.getUser                          avgt       3   3.523 ± 0.937   ms/op
ClientPb.listUser                         avgt       3   4.010 ± 1.571   ms/op
ClientPb.createUser                     sample  271947   3.529 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.298           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.242           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.216           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.064           ms/op
ClientPb.existUser                      sample  275035   3.488 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.114           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.994           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.032           ms/op
ClientPb.getUser                        sample  277573   3.455 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.341           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.248           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.213           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  232083   4.131 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.021           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
