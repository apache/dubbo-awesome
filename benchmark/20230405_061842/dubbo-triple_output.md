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
# Warmup Iteration   1: 1.973 ops/ms
# Warmup Iteration   2: 5.326 ops/ms
# Warmup Iteration   3: 8.712 ops/ms
Iteration   1: 8.928 ops/ms
Iteration   2: 9.407 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.312 ±(99.9%) 6.307 ops/ms [Average]
  (min, avg, max) = (8.928, 9.312, 9.600), stdev = 0.346
  CI (99.9%): [3.005, 15.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.105 ops/ms
# Warmup Iteration   2: 9.045 ops/ms
# Warmup Iteration   3: 9.393 ops/ms
Iteration   1: 9.453 ops/ms
Iteration   2: 9.725 ops/ms
Iteration   3: 9.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.530 ±(99.9%) 3.116 ops/ms [Average]
  (min, avg, max) = (9.411, 9.530, 9.725), stdev = 0.171
  CI (99.9%): [6.414, 12.646] (assumes normal distribution)


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
# Warmup Iteration   1: 2.594 ops/ms
# Warmup Iteration   2: 7.627 ops/ms
# Warmup Iteration   3: 9.258 ops/ms
Iteration   1: 9.678 ops/ms
Iteration   2: 9.563 ops/ms
Iteration   3: 9.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.590 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (9.530, 9.590, 9.678), stdev = 0.078
  CI (99.9%): [8.175, 11.005] (assumes normal distribution)


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
# Warmup Iteration   1: 2.544 ops/ms
# Warmup Iteration   2: 6.921 ops/ms
# Warmup Iteration   3: 7.618 ops/ms
Iteration   1: 7.961 ops/ms
Iteration   2: 7.812 ops/ms
Iteration   3: 8.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.955 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (7.812, 7.955, 8.092), stdev = 0.140
  CI (99.9%): [5.402, 10.509] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.273 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.012 ms/op
Iteration   1: 3.459 ±(99.9%) 0.011 ms/op
Iteration   2: 3.471 ±(99.9%) 0.004 ms/op
Iteration   3: 3.459 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.463 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (3.459, 3.463, 3.471), stdev = 0.007
  CI (99.9%): [3.338, 3.588] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.497 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.006 ms/op
Iteration   1: 3.404 ±(99.9%) 0.006 ms/op
Iteration   2: 3.285 ±(99.9%) 0.007 ms/op
Iteration   3: 3.314 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.334 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.285, 3.334, 3.404), stdev = 0.062
  CI (99.9%): [2.199, 4.470] (assumes normal distribution)


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
# Warmup Iteration   1: 10.673 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.825 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.003 ms/op
Iteration   1: 3.461 ±(99.9%) 0.009 ms/op
Iteration   2: 3.454 ±(99.9%) 0.011 ms/op
Iteration   3: 3.606 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.507 ±(99.9%) 1.558 ms/op [Average]
  (min, avg, max) = (3.454, 3.507, 3.606), stdev = 0.085
  CI (99.9%): [1.949, 5.066] (assumes normal distribution)


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
# Warmup Iteration   1: 12.576 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.672 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.008 ms/op
Iteration   1: 3.935 ±(99.9%) 0.010 ms/op
Iteration   2: 3.842 ±(99.9%) 0.012 ms/op
Iteration   3: 3.844 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.873 ±(99.9%) 0.969 ms/op [Average]
  (min, avg, max) = (3.842, 3.873, 3.935), stdev = 0.053
  CI (99.9%): [2.905, 4.842] (assumes normal distribution)


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
# Warmup Iteration   1: 9.487 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.387 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  18.305 ms/op
                 createUser·p0.9999: 20.826 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 3.425 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.682 ms/op
                 createUser·p0.999:  19.843 ms/op
                 createUser·p0.9999: 25.568 ms/op
                 createUser·p1.00:   25.854 ms/op

Iteration   3: 3.494 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  17.897 ms/op
                 createUser·p0.9999: 36.897 ms/op
                 createUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279245
  mean =      3.434 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4311 
    [ 2.500,  5.000) = 268496 
    [ 5.000,  7.500) = 5403 
    [ 7.500, 10.000) = 645 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     18.228 ms/op
     p(99.9900) =     35.329 ms/op
     p(99.9990) =     37.121 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 9.655 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
Iteration   1: 3.418 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  18.265 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   22.249 ms/op

Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  19.469 ms/op
                 existUser·p0.9999: 35.848 ms/op
                 existUser·p1.00:   35.914 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  11.576 ms/op
                 existUser·p0.9999: 23.668 ms/op
                 existUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286885
  mean =      3.345 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17021 
    [ 2.500,  5.000) = 264931 
    [ 5.000,  7.500) = 4234 
    [ 7.500, 10.000) = 328 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     11.600 ms/op
     p(99.9900) =     34.558 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 8.625 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.386 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  20.268 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  20.969 ms/op
                 getUser·p0.9999: 25.079 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.548 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 27.164 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277804
  mean =      3.455 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4966 
    [ 2.500,  5.000) = 266392 
    [ 5.000,  7.500) = 5166 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     18.225 ms/op
     p(99.9900) =     25.894 ms/op
     p(99.9990) =     27.405 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 11.145 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
Iteration   1: 4.032 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.036 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.981 ms/op
                 listUser·p0.9999: 21.208 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 3.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 4.076 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 21.239 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238737
  mean =      4.020 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 229841 
    [ 5.000,  7.500) = 6599 
    [ 7.500, 10.000) = 1558 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.036 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     14.619 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     22.073 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.312 ± 6.307  ops/ms
ClientPb.existUser                       thrpt       3   9.530 ± 3.116  ops/ms
ClientPb.getUser                         thrpt       3   9.590 ± 1.415  ops/ms
ClientPb.listUser                        thrpt       3   7.955 ± 2.554  ops/ms
ClientPb.createUser                       avgt       3   3.463 ± 0.125   ms/op
ClientPb.existUser                        avgt       3   3.334 ± 1.135   ms/op
ClientPb.getUser                          avgt       3   3.507 ± 1.558   ms/op
ClientPb.listUser                         avgt       3   3.873 ± 0.969   ms/op
ClientPb.createUser                     sample  279245   3.434 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.228           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.329           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  286885   3.345 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.600           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.558           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914           ms/op
ClientPb.getUser                        sample  277804   3.455 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.167           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.225           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.820           ms/op
ClientPb.listUser                       sample  238737   4.020 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.036           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.619           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.037           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.086           ms/op
