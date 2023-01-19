# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.234 ops/ms
# Warmup Iteration   2: 2.490 ops/ms
# Warmup Iteration   3: 5.447 ops/ms
Iteration   1: 5.591 ops/ms
Iteration   2: 5.665 ops/ms
Iteration   3: 5.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.710 ±(99.9%) 2.681 ops/ms [Average]
  (min, avg, max) = (5.591, 5.710, 5.874), stdev = 0.147
  CI (99.9%): [3.029, 8.391] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 4.958 ops/ms
# Warmup Iteration   3: 6.203 ops/ms
Iteration   1: 6.102 ops/ms
Iteration   2: 6.286 ops/ms
Iteration   3: 6.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.293 ±(99.9%) 3.554 ops/ms [Average]
  (min, avg, max) = (6.102, 6.293, 6.491), stdev = 0.195
  CI (99.9%): [2.739, 9.847] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.566 ops/ms
# Warmup Iteration   2: 4.358 ops/ms
# Warmup Iteration   3: 5.701 ops/ms
Iteration   1: 5.728 ops/ms
Iteration   2: 5.683 ops/ms
Iteration   3: 5.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.767 ±(99.9%) 2.007 ops/ms [Average]
  (min, avg, max) = (5.683, 5.767, 5.892), stdev = 0.110
  CI (99.9%): [3.761, 7.774] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.590 ops/ms
# Warmup Iteration   2: 3.817 ops/ms
# Warmup Iteration   3: 4.833 ops/ms
Iteration   1: 4.870 ops/ms
Iteration   2: 4.774 ops/ms
Iteration   3: 5.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.925 ±(99.9%) 3.368 ops/ms [Average]
  (min, avg, max) = (4.774, 4.925, 5.130), stdev = 0.185
  CI (99.9%): [1.557, 8.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.500 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.510 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.734 ±(99.9%) 0.018 ms/op
Iteration   1: 5.223 ±(99.9%) 0.024 ms/op
Iteration   2: 5.379 ±(99.9%) 0.017 ms/op
Iteration   3: 5.246 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.283 ±(99.9%) 1.543 ms/op [Average]
  (min, avg, max) = (5.223, 5.283, 5.379), stdev = 0.085
  CI (99.9%): [3.740, 6.825] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 14.666 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.754 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.351 ±(99.9%) 0.011 ms/op
Iteration   1: 5.211 ±(99.9%) 0.012 ms/op
Iteration   2: 5.019 ±(99.9%) 0.011 ms/op
Iteration   3: 5.096 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.109 ±(99.9%) 1.763 ms/op [Average]
  (min, avg, max) = (5.019, 5.109, 5.211), stdev = 0.097
  CI (99.9%): [3.345, 6.872] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.465 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 6.707 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.575 ±(99.9%) 0.011 ms/op
Iteration   1: 5.558 ±(99.9%) 0.012 ms/op
Iteration   2: 5.539 ±(99.9%) 0.008 ms/op
Iteration   3: 5.287 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.462 ±(99.9%) 2.765 ms/op [Average]
  (min, avg, max) = (5.287, 5.462, 5.558), stdev = 0.152
  CI (99.9%): [2.697, 8.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.850 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.502 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.132 ±(99.9%) 0.020 ms/op
Iteration   1: 6.363 ±(99.9%) 0.013 ms/op
Iteration   2: 5.944 ±(99.9%) 0.014 ms/op
Iteration   3: 6.566 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.291 ±(99.9%) 5.782 ms/op [Average]
  (min, avg, max) = (5.944, 6.291, 6.566), stdev = 0.317
  CI (99.9%): [0.508, 12.073] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.896 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 7.397 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.080 ±(99.9%) 0.026 ms/op
Iteration   1: 5.615 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.429 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.881 ms/op
                 createUser·p0.99:   10.519 ms/op
                 createUser·p0.999:  26.280 ms/op
                 createUser·p0.9999: 29.606 ms/op
                 createUser·p1.00:   31.687 ms/op

Iteration   2: 5.367 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.209 ms/op
                 createUser·p0.99:   9.539 ms/op
                 createUser·p0.999:  26.116 ms/op
                 createUser·p0.9999: 29.595 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   3: 5.540 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  15.340 ms/op
                 createUser·p0.9999: 31.145 ms/op
                 createUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174265
  mean =      5.506 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 64365 
    [ 5.000,  7.500) = 100844 
    [ 7.500, 10.000) = 7139 
    [10.000, 12.500) = 1311 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.561 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     17.363 ms/op
     p(99.9900) =     30.432 ms/op
     p(99.9990) =     31.443 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.912 ±(99.9%) 0.330 ms/op
# Warmup Iteration   2: 6.450 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.358 ±(99.9%) 0.016 ms/op
Iteration   1: 5.167 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   6.873 ms/op
                 existUser·p0.99:   9.944 ms/op
                 existUser·p0.999:  25.894 ms/op
                 existUser·p0.9999: 36.126 ms/op
                 existUser·p1.00:   37.028 ms/op

Iteration   2: 5.127 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   7.168 ms/op
                 existUser·p0.99:   9.599 ms/op
                 existUser·p0.999:  24.770 ms/op
                 existUser·p0.9999: 28.951 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   3: 5.225 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  26.896 ms/op
                 existUser·p0.9999: 29.786 ms/op
                 existUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185514
  mean =      5.173 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 103935 
    [ 5.000,  7.500) = 73908 
    [ 7.500, 10.000) = 5982 
    [10.000, 12.500) = 1139 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      7.102 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     25.214 ms/op
     p(99.9900) =     33.780 ms/op
     p(99.9990) =     37.028 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.699 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 6.396 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.244 ±(99.9%) 0.031 ms/op
Iteration   1: 5.383 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.875 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.750 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.534 ms/op
                 getUser·p0.999:  26.627 ms/op
                 getUser·p0.9999: 30.948 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   2: 5.363 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.724 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   6.949 ms/op
                 getUser·p0.99:   10.306 ms/op
                 getUser·p0.999:  29.050 ms/op
                 getUser·p0.9999: 38.812 ms/op
                 getUser·p1.00:   39.453 ms/op

Iteration   3: 5.438 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.613 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.291 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   9.814 ms/op
                 getUser·p0.999:  14.831 ms/op
                 getUser·p0.9999: 33.237 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177852
  mean =      5.394 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 72710 
    [ 5.000,  7.500) = 95723 
    [ 7.500, 10.000) = 7190 
    [10.000, 12.500) = 1463 
    [12.500, 15.000) = 437 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      2.613 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     17.339 ms/op
     p(99.9900) =     36.794 ms/op
     p(99.9990) =     39.402 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.832 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 7.829 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.615 ±(99.9%) 0.024 ms/op
Iteration   1: 6.523 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.207 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   9.617 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  31.225 ms/op
                 listUser·p0.9999: 35.193 ms/op
                 listUser·p1.00:   35.652 ms/op

Iteration   2: 6.566 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  30.587 ms/op
                 listUser·p0.9999: 36.119 ms/op
                 listUser·p1.00:   38.011 ms/op

Iteration   3: 6.446 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.031 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.471 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  25.409 ms/op
                 listUser·p0.9999: 28.642 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147330
  mean =      6.511 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4236 
    [ 5.000,  7.500) = 127014 
    [ 7.500, 10.000) = 11252 
    [10.000, 12.500) = 3489 
    [12.500, 15.000) = 741 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      3.031 ms/op
     p(50.0000) =      6.210 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      9.093 ms/op
     p(99.0000) =     12.255 ms/op
     p(99.9000) =     28.639 ms/op
     p(99.9900) =     35.210 ms/op
     p(99.9990) =     37.794 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.710 ± 2.681  ops/ms
ClientPb.existUser                       thrpt       3   6.293 ± 3.554  ops/ms
ClientPb.getUser                         thrpt       3   5.767 ± 2.007  ops/ms
ClientPb.listUser                        thrpt       3   4.925 ± 3.368  ops/ms
ClientPb.createUser                       avgt       3   5.283 ± 1.543   ms/op
ClientPb.existUser                        avgt       3   5.109 ± 1.763   ms/op
ClientPb.getUser                          avgt       3   5.462 ± 2.765   ms/op
ClientPb.listUser                         avgt       3   6.291 ± 5.782   ms/op
ClientPb.createUser                     sample  174265   5.506 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.302           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.561           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.191           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.363           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.432           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.687           ms/op
ClientPb.existUser                      sample  185514   5.173 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.102           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.716           ms/op
ClientPb.existUser:existUser·p0.999     sample          25.214           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.780           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.028           ms/op
ClientPb.getUser                        sample  177852   5.394 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.613           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.600           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.339           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.794           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.453           ms/op
ClientPb.listUser                       sample  147330   6.511 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.093           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.255           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.639           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.210           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.011           ms/op
