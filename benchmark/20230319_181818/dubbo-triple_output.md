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
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 6.530 ops/ms
# Warmup Iteration   3: 9.228 ops/ms
Iteration   1: 9.759 ops/ms
Iteration   2: 10.213 ops/ms
Iteration   3: 9.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.929 ±(99.9%) 4.518 ops/ms [Average]
  (min, avg, max) = (9.759, 9.929, 10.213), stdev = 0.248
  CI (99.9%): [5.411, 14.447] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 10.337 ops/ms
Iteration   1: 10.305 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.351 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (10.305, 10.351, 10.439), stdev = 0.077
  CI (99.9%): [8.954, 11.748] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.668 ops/ms
# Warmup Iteration   2: 8.979 ops/ms
# Warmup Iteration   3: 9.905 ops/ms
Iteration   1: 10.159 ops/ms
Iteration   2: 10.140 ops/ms
Iteration   3: 10.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.180 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (10.140, 10.180, 10.243), stdev = 0.055
  CI (99.9%): [9.182, 11.179] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 7.841 ops/ms
# Warmup Iteration   3: 8.439 ops/ms
Iteration   1: 8.789 ops/ms
Iteration   2: 8.660 ops/ms
Iteration   3: 8.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.663 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (8.541, 8.663, 8.789), stdev = 0.124
  CI (99.9%): [6.402, 10.925] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.807 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
Iteration   1: 3.113 ±(99.9%) 0.005 ms/op
Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
Iteration   3: 3.259 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.186 ±(99.9%) 1.334 ms/op [Average]
  (min, avg, max) = (3.113, 3.186, 3.259), stdev = 0.073
  CI (99.9%): [1.853, 4.520] (assumes normal distribution)


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
# Warmup Iteration   1: 7.360 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.005 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
Iteration   3: 2.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.000 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (2.973, 3.000, 3.024), stdev = 0.025
  CI (99.9%): [2.535, 3.464] (assumes normal distribution)


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
# Warmup Iteration   1: 7.756 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.002 ms/op
Iteration   1: 3.212 ±(99.9%) 0.006 ms/op
Iteration   2: 3.266 ±(99.9%) 0.004 ms/op
Iteration   3: 3.332 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.270 ±(99.9%) 1.092 ms/op [Average]
  (min, avg, max) = (3.212, 3.270, 3.332), stdev = 0.060
  CI (99.9%): [2.178, 4.362] (assumes normal distribution)


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
# Warmup Iteration   1: 9.479 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.008 ms/op
Iteration   1: 3.764 ±(99.9%) 0.008 ms/op
Iteration   2: 3.706 ±(99.9%) 0.010 ms/op
Iteration   3: 3.596 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.689 ±(99.9%) 1.562 ms/op [Average]
  (min, avg, max) = (3.596, 3.689, 3.764), stdev = 0.086
  CI (99.9%): [2.127, 5.250] (assumes normal distribution)


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
# Warmup Iteration   1: 7.041 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  11.076 ms/op
                 createUser·p0.9999: 20.964 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  19.467 ms/op
                 createUser·p0.9999: 25.867 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  14.467 ms/op
                 createUser·p0.9999: 23.813 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301039
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23183 
    [ 2.500,  5.000) = 272712 
    [ 5.000,  7.500) = 4262 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     24.602 ms/op
     p(99.9990) =     26.181 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 6.783 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   4.882 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  11.846 ms/op
                 existUser·p0.9999: 20.879 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   3: 3.163 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  16.090 ms/op
                 existUser·p0.9999: 24.326 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312077
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14293 
    [ 2.500,  5.000) = 292345 
    [ 5.000,  7.500) = 4668 
    [ 7.500, 10.000) = 329 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     14.700 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     25.605 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 7.404 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.012 ms/op
Iteration   1: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  12.861 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  15.286 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.816 ms/op
                 getUser·p0.999:  11.632 ms/op
                 getUser·p0.9999: 21.216 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299924
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13162 
    [ 2.500,  5.000) = 278587 
    [ 5.000,  7.500) = 7101 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      6.011 ms/op
     p(99.9000) =     13.110 ms/op
     p(99.9900) =     21.529 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 9.001 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.010 ms/op
Iteration   1: 3.735 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 31.271 ms/op
                 listUser·p1.00:   32.506 ms/op

Iteration   2: 3.648 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.943 ms/op
                 listUser·p0.9999: 14.713 ms/op
                 listUser·p1.00:   15.335 ms/op

Iteration   3: 3.678 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.764 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 260237
  mean =      3.687 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 253456 
    [ 5.000,  7.500) = 4672 
    [ 7.500, 10.000) = 1376 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     28.695 ms/op
     p(99.9990) =     32.197 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.929 ± 4.518  ops/ms
ClientPb.existUser                       thrpt       3  10.351 ± 1.397  ops/ms
ClientPb.getUser                         thrpt       3  10.180 ± 0.999  ops/ms
ClientPb.listUser                        thrpt       3   8.663 ± 2.262  ops/ms
ClientPb.createUser                       avgt       3   3.186 ± 1.334   ms/op
ClientPb.existUser                        avgt       3   3.000 ± 0.464   ms/op
ClientPb.getUser                          avgt       3   3.270 ± 1.092   ms/op
ClientPb.listUser                         avgt       3   3.689 ± 1.562   ms/op
ClientPb.createUser                     sample  301039   3.185 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.467           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.602           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  312077   3.073 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.898           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.700           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.463           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.690           ms/op
ClientPb.getUser                        sample  299924   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.028           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.523           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.011           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.110           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.529           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  260237   3.687 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.539           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.186           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.695           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.506           ms/op
