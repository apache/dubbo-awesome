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
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 6.236 ops/ms
# Warmup Iteration   3: 9.197 ops/ms
Iteration   1: 9.398 ops/ms
Iteration   2: 9.566 ops/ms
Iteration   3: 9.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.403 ±(99.9%) 2.921 ops/ms [Average]
  (min, avg, max) = (9.245, 9.403, 9.566), stdev = 0.160
  CI (99.9%): [6.482, 12.324] (assumes normal distribution)


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
# Warmup Iteration   1: 2.929 ops/ms
# Warmup Iteration   2: 8.995 ops/ms
# Warmup Iteration   3: 9.697 ops/ms
Iteration   1: 9.861 ops/ms
Iteration   2: 9.804 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.907 ±(99.9%) 2.411 ops/ms [Average]
  (min, avg, max) = (9.804, 9.907, 10.056), stdev = 0.132
  CI (99.9%): [7.496, 12.318] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ops/ms
# Warmup Iteration   2: 8.661 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.091 ops/ms
Iteration   2: 9.618 ops/ms
Iteration   3: 9.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.390 ±(99.9%) 4.941 ops/ms [Average]
  (min, avg, max) = (9.091, 9.390, 9.618), stdev = 0.271
  CI (99.9%): [4.449, 14.330] (assumes normal distribution)


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
# Warmup Iteration   1: 3.183 ops/ms
# Warmup Iteration   2: 7.405 ops/ms
# Warmup Iteration   3: 7.853 ops/ms
Iteration   1: 8.124 ops/ms
Iteration   2: 7.931 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.066 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (7.931, 8.066, 8.144), stdev = 0.118
  CI (99.9%): [5.922, 10.210] (assumes normal distribution)


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
# Warmup Iteration   1: 8.786 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.008 ms/op
Iteration   1: 3.517 ±(99.9%) 0.005 ms/op
Iteration   2: 3.363 ±(99.9%) 0.009 ms/op
Iteration   3: 3.366 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.415 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (3.363, 3.415, 3.517), stdev = 0.088
  CI (99.9%): [1.807, 5.024] (assumes normal distribution)


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
# Warmup Iteration   1: 8.518 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.009 ms/op
Iteration   1: 3.289 ±(99.9%) 0.005 ms/op
Iteration   2: 3.300 ±(99.9%) 0.007 ms/op
Iteration   3: 3.327 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.305 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (3.289, 3.305, 3.327), stdev = 0.020
  CI (99.9%): [2.945, 3.666] (assumes normal distribution)


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
# Warmup Iteration   1: 8.664 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.009 ms/op
Iteration   1: 3.413 ±(99.9%) 0.008 ms/op
Iteration   2: 3.409 ±(99.9%) 0.010 ms/op
Iteration   3: 3.440 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.421 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.409, 3.421, 3.440), stdev = 0.017
  CI (99.9%): [3.117, 3.724] (assumes normal distribution)


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
# Warmup Iteration   1: 9.077 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.012 ms/op
Iteration   1: 3.873 ±(99.9%) 0.011 ms/op
Iteration   2: 3.832 ±(99.9%) 0.015 ms/op
Iteration   3: 4.070 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.925 ±(99.9%) 2.321 ms/op [Average]
  (min, avg, max) = (3.832, 3.925, 4.070), stdev = 0.127
  CI (99.9%): [1.604, 6.246] (assumes normal distribution)


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
# Warmup Iteration   1: 8.427 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
Iteration   1: 3.603 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  19.538 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.518 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  21.893 ms/op
                 createUser·p0.9999: 28.234 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   3: 3.561 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  18.816 ms/op
                 createUser·p0.9999: 27.035 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269386
  mean =      3.560 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2127 
    [ 2.500,  5.000) = 258361 
    [ 5.000,  7.500) = 7601 
    [ 7.500, 10.000) = 815 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     19.262 ms/op
     p(99.9900) =     26.427 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 7.902 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
Iteration   1: 3.302 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  10.241 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.719 ms/op
                 existUser·p0.999:  10.616 ms/op
                 existUser·p0.9999: 32.404 ms/op
                 existUser·p1.00:   32.866 ms/op

Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  21.581 ms/op
                 existUser·p0.9999: 31.359 ms/op
                 existUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289505
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5273 
    [ 2.500,  5.000) = 280383 
    [ 5.000,  7.500) = 3124 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     11.010 ms/op
     p(99.9900) =     31.916 ms/op
     p(99.9990) =     32.778 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 9.472 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.010 ms/op
Iteration   1: 3.369 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  17.341 ms/op
                 getUser·p0.9999: 22.629 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   2: 3.299 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  15.458 ms/op
                 getUser·p0.9999: 26.356 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.412 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  18.241 ms/op
                 getUser·p0.9999: 28.594 ms/op
                 getUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285334
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2442 
    [ 2.500,  5.000) = 278040 
    [ 5.000,  7.500) = 4069 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     17.411 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     29.014 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 10.800 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.410 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.286 ±(99.9%) 0.015 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  18.578 ms/op
                 listUser·p0.9999: 22.377 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  16.303 ms/op
                 listUser·p0.9999: 21.070 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 3.893 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   6.384 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 15.791 ms/op
                 listUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244143
  mean =      3.934 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 235867 
    [ 5.000,  7.500) = 6372 
    [ 7.500, 10.000) = 1041 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     15.366 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     22.698 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.403 ± 2.921  ops/ms
ClientPb.existUser                       thrpt       3   9.907 ± 2.411  ops/ms
ClientPb.getUser                         thrpt       3   9.390 ± 4.941  ops/ms
ClientPb.listUser                        thrpt       3   8.066 ± 2.144  ops/ms
ClientPb.createUser                       avgt       3   3.415 ± 1.609   ms/op
ClientPb.existUser                        avgt       3   3.305 ± 0.361   ms/op
ClientPb.getUser                          avgt       3   3.421 ± 0.303   ms/op
ClientPb.listUser                         avgt       3   3.925 ± 2.321   ms/op
ClientPb.createUser                     sample  269386   3.560 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.344           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.182           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.262           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.427           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.738           ms/op
ClientPb.existUser                      sample  289505   3.315 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.010           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.916           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.866           ms/op
ClientPb.getUser                        sample  285334   3.359 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.362           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.252           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.411           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.313           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.523           ms/op
ClientPb.listUser                       sample  244143   3.934 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.908           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.996           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.366           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.758           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.807           ms/op
