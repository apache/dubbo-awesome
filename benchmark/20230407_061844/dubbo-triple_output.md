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
# Warmup Iteration   1: 1.856 ops/ms
# Warmup Iteration   2: 5.296 ops/ms
# Warmup Iteration   3: 8.652 ops/ms
Iteration   1: 9.176 ops/ms
Iteration   2: 9.354 ops/ms
Iteration   3: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.321 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (9.176, 9.321, 9.433), stdev = 0.132
  CI (99.9%): [6.919, 11.723] (assumes normal distribution)


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
# Warmup Iteration   1: 2.655 ops/ms
# Warmup Iteration   2: 8.640 ops/ms
# Warmup Iteration   3: 9.261 ops/ms
Iteration   1: 9.743 ops/ms
Iteration   2: 9.560 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.654 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (9.560, 9.654, 9.743), stdev = 0.092
  CI (99.9%): [7.984, 11.324] (assumes normal distribution)


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
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 8.214 ops/ms
# Warmup Iteration   3: 8.788 ops/ms
Iteration   1: 8.767 ops/ms
Iteration   2: 9.115 ops/ms
Iteration   3: 8.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.944 ±(99.9%) 3.183 ops/ms [Average]
  (min, avg, max) = (8.767, 8.944, 9.115), stdev = 0.174
  CI (99.9%): [5.760, 12.127] (assumes normal distribution)


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
# Warmup Iteration   1: 2.785 ops/ms
# Warmup Iteration   2: 7.520 ops/ms
# Warmup Iteration   3: 7.944 ops/ms
Iteration   1: 7.847 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.865 ±(99.9%) 2.825 ops/ms [Average]
  (min, avg, max) = (7.720, 7.865, 8.028), stdev = 0.155
  CI (99.9%): [5.040, 10.690] (assumes normal distribution)


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
# Warmup Iteration   1: 10.669 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.004 ms/op
Iteration   1: 3.381 ±(99.9%) 0.010 ms/op
Iteration   2: 3.515 ±(99.9%) 0.006 ms/op
Iteration   3: 3.455 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 1.228 ms/op [Average]
  (min, avg, max) = (3.381, 3.450, 3.515), stdev = 0.067
  CI (99.9%): [2.223, 4.678] (assumes normal distribution)


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
# Warmup Iteration   1: 11.176 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.006 ms/op
Iteration   1: 3.339 ±(99.9%) 0.003 ms/op
Iteration   2: 3.234 ±(99.9%) 0.010 ms/op
Iteration   3: 3.320 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 1.022 ms/op [Average]
  (min, avg, max) = (3.234, 3.298, 3.339), stdev = 0.056
  CI (99.9%): [2.276, 4.320] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.445 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.006 ms/op
Iteration   1: 3.617 ±(99.9%) 0.006 ms/op
Iteration   2: 3.351 ±(99.9%) 0.005 ms/op
Iteration   3: 3.521 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.496 ±(99.9%) 2.454 ms/op [Average]
  (min, avg, max) = (3.351, 3.496, 3.617), stdev = 0.135
  CI (99.9%): [1.042, 5.950] (assumes normal distribution)


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
# Warmup Iteration   1: 10.718 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
Iteration   2: 4.017 ±(99.9%) 0.008 ms/op
Iteration   3: 4.020 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.990, 4.009, 4.020), stdev = 0.016
  CI (99.9%): [3.710, 4.308] (assumes normal distribution)


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
# Warmup Iteration   1: 9.618 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
Iteration   1: 3.313 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.714 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  16.205 ms/op
                 createUser·p0.9999: 24.042 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   2: 3.420 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  22.723 ms/op
                 createUser·p0.9999: 25.632 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.432 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.866 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 34.189 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283260
  mean =      3.387 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11161 
    [ 2.500,  5.000) = 265172 
    [ 5.000,  7.500) = 5903 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 175 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     34.680 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 9.302 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.433 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  9.322 ms/op
                 existUser·p0.9999: 23.968 ms/op
                 existUser·p1.00:   24.510 ms/op

Iteration   2: 3.349 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  23.538 ms/op
                 existUser·p0.9999: 33.439 ms/op
                 existUser·p1.00:   34.341 ms/op

Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  12.681 ms/op
                 existUser·p0.9999: 29.458 ms/op
                 existUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287625
  mean =      3.334 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6680 
    [ 2.500,  5.000) = 275534 
    [ 5.000,  7.500) = 4304 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     11.557 ms/op
     p(99.9900) =     31.059 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 10.565 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.011 ms/op
Iteration   1: 3.588 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.874 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   5.349 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  20.797 ms/op
                 getUser·p0.9999: 23.562 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.536 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  24.001 ms/op
                 getUser·p0.9999: 29.772 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   3: 3.587 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  25.264 ms/op
                 getUser·p0.9999: 29.418 ms/op
                 getUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269019
  mean =      3.570 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8772 
    [ 2.500,  5.000) = 248244 
    [ 5.000,  7.500) = 9923 
    [ 7.500, 10.000) = 1441 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     21.070 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 9.636 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.014 ms/op
Iteration   1: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  18.574 ms/op
                 listUser·p0.9999: 23.738 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.970 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 4.065 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   8.118 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 16.311 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238445
  mean =      4.025 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 229449 
    [ 5.000,  7.500) = 6323 
    [ 7.500, 10.000) = 1803 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     23.051 ms/op
     p(99.9990) =     24.382 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.321 ± 2.402  ops/ms
ClientPb.existUser                       thrpt       3   9.654 ± 1.670  ops/ms
ClientPb.getUser                         thrpt       3   8.944 ± 3.183  ops/ms
ClientPb.listUser                        thrpt       3   7.865 ± 2.825  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 1.228   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 1.022   ms/op
ClientPb.getUser                          avgt       3   3.496 ± 2.454   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 0.299   ms/op
ClientPb.createUser                     sample  283260   3.387 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.174           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.561           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.260           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  287625   3.334 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.751           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.557           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.059           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.341           ms/op
ClientPb.getUser                        sample  269019   3.570 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.070           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.196           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  238445   4.025 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.051           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
