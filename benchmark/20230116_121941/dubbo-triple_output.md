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
# Warmup Iteration   1: 2.133 ops/ms
# Warmup Iteration   2: 5.577 ops/ms
# Warmup Iteration   3: 8.294 ops/ms
Iteration   1: 8.915 ops/ms
Iteration   2: 9.102 ops/ms
Iteration   3: 9.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.091 ±(99.9%) 3.113 ops/ms [Average]
  (min, avg, max) = (8.915, 9.091, 9.256), stdev = 0.171
  CI (99.9%): [5.978, 12.204] (assumes normal distribution)


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
# Warmup Iteration   1: 2.511 ops/ms
# Warmup Iteration   2: 8.356 ops/ms
# Warmup Iteration   3: 9.228 ops/ms
Iteration   1: 9.337 ops/ms
Iteration   2: 9.580 ops/ms
Iteration   3: 9.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.453 ±(99.9%) 2.225 ops/ms [Average]
  (min, avg, max) = (9.337, 9.453, 9.580), stdev = 0.122
  CI (99.9%): [7.228, 11.677] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 7.363 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.293 ops/ms
Iteration   2: 9.007 ops/ms
Iteration   3: 8.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.055 ±(99.9%) 3.975 ops/ms [Average]
  (min, avg, max) = (8.865, 9.055, 9.293), stdev = 0.218
  CI (99.9%): [5.080, 13.030] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 6.794 ops/ms
# Warmup Iteration   3: 7.106 ops/ms
Iteration   1: 7.590 ops/ms
Iteration   2: 7.932 ops/ms
Iteration   3: 7.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.731 ±(99.9%) 3.261 ops/ms [Average]
  (min, avg, max) = (7.590, 7.731, 7.932), stdev = 0.179
  CI (99.9%): [4.470, 10.993] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.668 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.009 ms/op
Iteration   1: 3.581 ±(99.9%) 0.008 ms/op
Iteration   2: 3.534 ±(99.9%) 0.006 ms/op
Iteration   3: 3.471 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.529 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.471, 3.529, 3.581), stdev = 0.056
  CI (99.9%): [2.514, 4.543] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.031 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.802 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.004 ms/op
Iteration   1: 3.337 ±(99.9%) 0.005 ms/op
Iteration   2: 3.404 ±(99.9%) 0.003 ms/op
Iteration   3: 3.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.399 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.337, 3.399, 3.457), stdev = 0.060
  CI (99.9%): [2.308, 4.490] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.237 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.003 ms/op
Iteration   1: 3.699 ±(99.9%) 0.004 ms/op
Iteration   2: 3.447 ±(99.9%) 0.006 ms/op
Iteration   3: 3.495 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.547 ±(99.9%) 2.440 ms/op [Average]
  (min, avg, max) = (3.447, 3.547, 3.699), stdev = 0.134
  CI (99.9%): [1.106, 5.987] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.349 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.437 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.008 ms/op
Iteration   1: 4.234 ±(99.9%) 0.006 ms/op
Iteration   2: 4.184 ±(99.9%) 0.008 ms/op
Iteration   3: 4.065 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.161 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (4.065, 4.161, 4.234), stdev = 0.087
  CI (99.9%): [2.574, 5.748] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.112 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.013 ms/op
Iteration   1: 3.534 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  23.069 ms/op
                 createUser·p0.9999: 26.967 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 3.585 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  24.406 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   3: 3.622 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.122 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  20.289 ms/op
                 createUser·p0.9999: 30.421 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267912
  mean =      3.580 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8732 
    [ 2.500,  5.000) = 251219 
    [ 5.000,  7.500) = 6966 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 146 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     28.496 ms/op
     p(99.9990) =     31.507 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 9.712 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  22.427 ms/op
                 existUser·p0.9999: 30.638 ms/op
                 existUser·p1.00:   31.654 ms/op

Iteration   2: 3.487 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  24.243 ms/op
                 existUser·p0.9999: 27.913 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.685 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  9.999 ms/op
                 existUser·p0.9999: 30.387 ms/op
                 existUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 273303
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6598 
    [ 2.500,  5.000) = 260363 
    [ 5.000,  7.500) = 5570 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     11.098 ms/op
     p(99.9900) =     30.125 ms/op
     p(99.9990) =     31.318 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.811 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.011 ms/op
Iteration   1: 3.710 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   8.020 ms/op
                 getUser·p0.999:  23.615 ms/op
                 getUser·p0.9999: 25.226 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.609 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  24.347 ms/op
                 getUser·p0.9999: 29.115 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   3: 3.472 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.865 ms/op
                 getUser·p0.999:  11.826 ms/op
                 getUser·p0.9999: 29.917 ms/op
                 getUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267131
  mean =      3.594 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 713 
    [ 2.500,  5.000) = 255283 
    [ 5.000,  7.500) = 8670 
    [ 7.500, 10.000) = 1836 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     23.003 ms/op
     p(99.9900) =     29.271 ms/op
     p(99.9990) =     31.053 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 12.166 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.592 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.352 ±(99.9%) 0.015 ms/op
Iteration   1: 4.208 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 28.810 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   2: 4.231 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.076 ms/op
                 listUser·p0.999:  18.297 ms/op
                 listUser·p0.9999: 21.802 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 4.092 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  17.561 ms/op
                 listUser·p0.9999: 21.213 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229616
  mean =      4.176 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 216128 
    [ 5.000,  7.500) = 10298 
    [ 7.500, 10.000) = 2117 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      8.092 ms/op
     p(99.9000) =     18.801 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     30.333 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.091 ± 3.113  ops/ms
ClientPb.existUser                       thrpt       3   9.453 ± 2.225  ops/ms
ClientPb.getUser                         thrpt       3   9.055 ± 3.975  ops/ms
ClientPb.listUser                        thrpt       3   7.731 ± 3.261  ops/ms
ClientPb.createUser                       avgt       3   3.529 ± 1.014   ms/op
ClientPb.existUser                        avgt       3   3.399 ± 1.091   ms/op
ClientPb.getUser                          avgt       3   3.547 ± 2.440   ms/op
ClientPb.listUser                         avgt       3   4.161 ± 1.587   ms/op
ClientPb.createUser                     sample  267912   3.580 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.122           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.889           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.496           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.375           ms/op
ClientPb.existUser                      sample  273303   3.508 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.339           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.448           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.098           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.125           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.687           ms/op
ClientPb.getUser                        sample  267131   3.594 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.370           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.430           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.003           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.271           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.130           ms/op
ClientPb.listUser                       sample  229616   4.176 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.401           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.177           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.092           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.801           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.359           ms/op
