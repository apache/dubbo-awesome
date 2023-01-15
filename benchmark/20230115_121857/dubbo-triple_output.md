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
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 6.058 ops/ms
# Warmup Iteration   3: 8.893 ops/ms
Iteration   1: 9.262 ops/ms
Iteration   2: 9.341 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.249 ±(99.9%) 1.808 ops/ms [Average]
  (min, avg, max) = (9.144, 9.249, 9.341), stdev = 0.099
  CI (99.9%): [7.441, 11.057] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ops/ms
# Warmup Iteration   2: 9.030 ops/ms
# Warmup Iteration   3: 9.639 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 9.714 ops/ms
Iteration   3: 10.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.809 ±(99.9%) 4.461 ops/ms [Average]
  (min, avg, max) = (9.627, 9.809, 10.087), stdev = 0.245
  CI (99.9%): [5.349, 14.270] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.650 ops/ms
# Warmup Iteration   2: 8.177 ops/ms
# Warmup Iteration   3: 8.970 ops/ms
Iteration   1: 9.626 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 9.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.524 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (9.382, 9.524, 9.626), stdev = 0.127
  CI (99.9%): [7.215, 11.834] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.943 ops/ms
# Warmup Iteration   2: 7.594 ops/ms
# Warmup Iteration   3: 7.666 ops/ms
Iteration   1: 7.810 ops/ms
Iteration   2: 8.136 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.954 ±(99.9%) 3.028 ops/ms [Average]
  (min, avg, max) = (7.810, 7.954, 8.136), stdev = 0.166
  CI (99.9%): [4.926, 10.983] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.830 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.002 ms/op
Iteration   1: 3.332 ±(99.9%) 0.012 ms/op
Iteration   2: 3.369 ±(99.9%) 0.007 ms/op
Iteration   3: 3.479 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.393 ±(99.9%) 1.394 ms/op [Average]
  (min, avg, max) = (3.332, 3.393, 3.479), stdev = 0.076
  CI (99.9%): [1.999, 4.788] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.427 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.006 ms/op
Iteration   1: 3.261 ±(99.9%) 0.004 ms/op
Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
Iteration   3: 3.223 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.238 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.223, 3.238, 3.261), stdev = 0.020
  CI (99.9%): [2.873, 3.603] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.421 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.007 ms/op
Iteration   1: 3.413 ±(99.9%) 0.011 ms/op
Iteration   2: 3.480 ±(99.9%) 0.007 ms/op
Iteration   3: 3.434 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.442 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.413, 3.442, 3.480), stdev = 0.035
  CI (99.9%): [2.811, 4.074] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.560 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.009 ms/op
Iteration   1: 3.911 ±(99.9%) 0.013 ms/op
Iteration   2: 3.848 ±(99.9%) 0.014 ms/op
Iteration   3: 3.966 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.908 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (3.848, 3.908, 3.966), stdev = 0.059
  CI (99.9%): [2.834, 4.982] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.932 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.004 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.010 ms/op
Iteration   1: 3.550 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  12.670 ms/op
                 createUser·p0.9999: 28.146 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   2: 3.538 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  23.069 ms/op
                 createUser·p0.9999: 32.930 ms/op
                 createUser·p1.00:   36.569 ms/op

Iteration   3: 3.483 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  19.597 ms/op
                 createUser·p0.9999: 27.289 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272412
  mean =      3.523 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9673 
    [ 2.500,  5.000) = 253081 
    [ 5.000,  7.500) = 8410 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     31.466 ms/op
     p(99.9990) =     35.295 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.562 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.008 ms/op
Iteration   1: 3.442 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  18.448 ms/op
                 existUser·p0.9999: 23.757 ms/op
                 existUser·p1.00:   24.576 ms/op

Iteration   2: 3.277 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  13.605 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  22.161 ms/op
                 existUser·p0.9999: 25.122 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283187
  mean =      3.389 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12288 
    [ 2.500,  5.000) = 263380 
    [ 5.000,  7.500) = 6709 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     18.475 ms/op
     p(99.9900) =     24.467 ms/op
     p(99.9990) =     26.160 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.253 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.836 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.010 ms/op
Iteration   1: 3.507 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  20.375 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  22.551 ms/op
                 getUser·p0.9999: 25.284 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.548 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.387 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  19.096 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275075
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7386 
    [ 2.500,  5.000) = 258922 
    [ 5.000,  7.500) = 7732 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     19.200 ms/op
     p(99.9900) =     25.952 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.410 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
Iteration   1: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  18.266 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   24.674 ms/op

Iteration   2: 4.081 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  15.690 ms/op
                 listUser·p0.9999: 18.618 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.053 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  13.780 ms/op
                 listUser·p0.9999: 15.911 ms/op
                 listUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236839
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 227062 
    [ 5.000,  7.500) = 7139 
    [ 7.500, 10.000) = 1790 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     15.423 ms/op
     p(99.9900) =     23.046 ms/op
     p(99.9990) =     23.741 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.249 ± 1.808  ops/ms
ClientPb.existUser                       thrpt       3   9.809 ± 4.461  ops/ms
ClientPb.getUser                         thrpt       3   9.524 ± 2.310  ops/ms
ClientPb.listUser                        thrpt       3   7.954 ± 3.028  ops/ms
ClientPb.createUser                       avgt       3   3.393 ± 1.394   ms/op
ClientPb.existUser                        avgt       3   3.238 ± 0.365   ms/op
ClientPb.getUser                          avgt       3   3.442 ± 0.631   ms/op
ClientPb.listUser                         avgt       3   3.908 ± 1.074   ms/op
ClientPb.createUser                     sample  272412   3.523 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.560           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.466           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  283187   3.389 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.046           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.448           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.062           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.475           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.492           ms/op
ClientPb.getUser                        sample  275075   3.489 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.387           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.200           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.952           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.623           ms/op
ClientPb.listUser                       sample  236839   4.054 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.989           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.809           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.423           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.046           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.674           ms/op
