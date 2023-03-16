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
# Warmup Iteration   1: 0.912 ops/ms
# Warmup Iteration   2: 2.067 ops/ms
# Warmup Iteration   3: 4.537 ops/ms
Iteration   1: 5.377 ops/ms
Iteration   2: 5.519 ops/ms
Iteration   3: 5.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.555 ±(99.9%) 3.640 ops/ms [Average]
  (min, avg, max) = (5.377, 5.555, 5.771), stdev = 0.199
  CI (99.9%): [1.916, 9.195] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.593 ops/ms
# Warmup Iteration   2: 4.606 ops/ms
# Warmup Iteration   3: 5.828 ops/ms
Iteration   1: 5.857 ops/ms
Iteration   2: 5.844 ops/ms
Iteration   3: 5.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.850 ±(99.9%) 0.122 ops/ms [Average]
  (min, avg, max) = (5.844, 5.850, 5.857), stdev = 0.007
  CI (99.9%): [5.729, 5.972] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.656 ops/ms
# Warmup Iteration   2: 4.301 ops/ms
# Warmup Iteration   3: 5.368 ops/ms
Iteration   1: 5.534 ops/ms
Iteration   2: 5.562 ops/ms
Iteration   3: 5.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.553 ±(99.9%) 0.305 ops/ms [Average]
  (min, avg, max) = (5.534, 5.553, 5.563), stdev = 0.017
  CI (99.9%): [5.248, 5.858] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.391 ops/ms
# Warmup Iteration   2: 3.559 ops/ms
# Warmup Iteration   3: 4.538 ops/ms
Iteration   1: 4.510 ops/ms
Iteration   2: 4.781 ops/ms
Iteration   3: 4.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.719 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (4.510, 4.719, 4.867), stdev = 0.186
  CI (99.9%): [1.325, 8.114] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.003 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.129 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.290 ±(99.9%) 0.010 ms/op
Iteration   1: 5.650 ±(99.9%) 0.016 ms/op
Iteration   2: 6.281 ±(99.9%) 0.007 ms/op
Iteration   3: 5.721 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.884 ±(99.9%) 6.308 ms/op [Average]
  (min, avg, max) = (5.650, 5.884, 6.281), stdev = 0.346
  CI (99.9%): [≈ 0, 12.192] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.907 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.314 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.451 ±(99.9%) 0.015 ms/op
Iteration   1: 5.342 ±(99.9%) 0.013 ms/op
Iteration   2: 5.291 ±(99.9%) 0.011 ms/op
Iteration   3: 5.479 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.371 ±(99.9%) 1.768 ms/op [Average]
  (min, avg, max) = (5.291, 5.371, 5.479), stdev = 0.097
  CI (99.9%): [3.603, 7.139] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.515 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.707 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.863 ±(99.9%) 0.010 ms/op
Iteration   1: 5.737 ±(99.9%) 0.009 ms/op
Iteration   2: 5.711 ±(99.9%) 0.010 ms/op
Iteration   3: 5.602 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.683 ±(99.9%) 1.302 ms/op [Average]
  (min, avg, max) = (5.602, 5.683, 5.737), stdev = 0.071
  CI (99.9%): [4.381, 6.986] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.089 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 9.167 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 7.153 ±(99.9%) 0.010 ms/op
Iteration   1: 7.011 ±(99.9%) 0.014 ms/op
Iteration   2: 6.760 ±(99.9%) 0.024 ms/op
Iteration   3: 6.431 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.734 ±(99.9%) 5.302 ms/op [Average]
  (min, avg, max) = (6.431, 6.734, 7.011), stdev = 0.291
  CI (99.9%): [1.433, 12.036] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 18.537 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 7.755 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.134 ±(99.9%) 0.026 ms/op
Iteration   1: 5.652 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.568 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   7.209 ms/op
                 createUser·p0.95:   8.316 ms/op
                 createUser·p0.99:   11.911 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 30.409 ms/op
                 createUser·p1.00:   32.080 ms/op

Iteration   2: 5.467 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.773 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.894 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  22.035 ms/op
                 createUser·p0.9999: 28.649 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 5.710 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.572 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   11.092 ms/op
                 createUser·p0.999:  26.342 ms/op
                 createUser·p0.9999: 29.832 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171239
  mean =      5.608 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 55101 
    [ 5.000,  7.500) = 104010 
    [ 7.500, 10.000) = 9195 
    [10.000, 12.500) = 1910 
    [12.500, 15.000) = 574 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.568 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      7.004 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     11.174 ms/op
     p(99.9000) =     18.302 ms/op
     p(99.9900) =     29.815 ms/op
     p(99.9990) =     31.753 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 19.188 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.638 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 5.818 ±(99.9%) 0.025 ms/op
Iteration   1: 5.639 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   7.971 ms/op
                 existUser·p0.99:   11.370 ms/op
                 existUser·p0.999:  24.104 ms/op
                 existUser·p0.9999: 30.397 ms/op
                 existUser·p1.00:   34.800 ms/op

Iteration   2: 5.565 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.654 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.685 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   10.437 ms/op
                 existUser·p0.999:  18.689 ms/op
                 existUser·p0.9999: 35.210 ms/op
                 existUser·p1.00:   37.093 ms/op

Iteration   3: 5.334 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.671 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.332 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  27.110 ms/op
                 existUser·p0.9999: 31.982 ms/op
                 existUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174000
  mean =      5.510 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 64293 
    [ 5.000,  7.500) = 100131 
    [ 7.500, 10.000) = 7129 
    [10.000, 12.500) = 1586 
    [12.500, 15.000) = 505 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.421 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     34.511 ms/op
     p(99.9990) =     35.832 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.149 ±(99.9%) 0.312 ms/op
# Warmup Iteration   2: 6.993 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.723 ±(99.9%) 0.020 ms/op
Iteration   1: 5.949 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.376 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.848 ms/op
                 getUser·p0.95:   9.273 ms/op
                 getUser·p0.99:   13.189 ms/op
                 getUser·p0.999:  23.493 ms/op
                 getUser·p0.9999: 29.106 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   2: 5.781 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.908 ms/op
                 getUser·p0.50:   5.562 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.717 ms/op
                 getUser·p0.99:   10.704 ms/op
                 getUser·p0.999:  24.194 ms/op
                 getUser·p0.9999: 29.408 ms/op
                 getUser·p1.00:   31.261 ms/op

Iteration   3: 5.486 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.512 ms/op
                 getUser·p0.99:   11.370 ms/op
                 getUser·p0.999:  24.798 ms/op
                 getUser·p0.9999: 29.103 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167453
  mean =      5.732 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 45999 
    [ 5.000,  7.500) = 109168 
    [ 7.500, 10.000) = 8668 
    [10.000, 12.500) = 2102 
    [12.500, 15.000) = 949 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     30.443 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.139 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 8.427 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.754 ±(99.9%) 0.026 ms/op
Iteration   1: 6.736 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  29.884 ms/op
                 listUser·p0.9999: 34.751 ms/op
                 listUser·p1.00:   36.372 ms/op

Iteration   2: 6.661 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.628 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  30.245 ms/op
                 listUser·p0.9999: 33.712 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 6.906 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.121 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.275 ms/op
                 listUser·p0.999:  23.041 ms/op
                 listUser·p0.9999: 32.219 ms/op
                 listUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141737
  mean =      6.766 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2169 
    [ 5.000,  7.500) = 116383 
    [ 7.500, 10.000) = 17394 
    [10.000, 12.500) = 4155 
    [12.500, 15.000) = 1060 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      6.390 ms/op
     p(90.0000) =      8.241 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     29.336 ms/op
     p(99.9900) =     33.740 ms/op
     p(99.9990) =     36.072 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.555 ± 3.640  ops/ms
ClientPb.existUser                       thrpt       3   5.850 ± 0.122  ops/ms
ClientPb.getUser                         thrpt       3   5.553 ± 0.305  ops/ms
ClientPb.listUser                        thrpt       3   4.719 ± 3.395  ops/ms
ClientPb.createUser                       avgt       3   5.884 ± 6.308   ms/op
ClientPb.existUser                        avgt       3   5.371 ± 1.768   ms/op
ClientPb.getUser                          avgt       3   5.683 ± 1.302   ms/op
ClientPb.listUser                         avgt       3   6.734 ± 5.302   ms/op
ClientPb.createUser                     sample  171239   5.608 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.004           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.086           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.302           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.815           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  174000   5.510 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.660           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.682           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.511           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.093           ms/op
ClientPb.getUser                        sample  167453   5.732 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.939           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.389           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.075           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.986           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.131           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.261           ms/op
ClientPb.listUser                       sample  141737   6.766 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.628           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.390           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.740           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.372           ms/op
