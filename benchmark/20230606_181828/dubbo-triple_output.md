# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 4.763 ops/ms
# Warmup Iteration   3: 8.454 ops/ms
Iteration   1: 9.312 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.420 ±(99.9%) 2.873 ops/ms [Average]
  (min, avg, max) = (9.312, 9.420, 9.601), stdev = 0.157
  CI (99.9%): [6.547, 12.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.961 ops/ms
# Warmup Iteration   2: 8.725 ops/ms
# Warmup Iteration   3: 9.801 ops/ms
Iteration   1: 9.644 ops/ms
Iteration   2: 9.790 ops/ms
Iteration   3: 9.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.729 ±(99.9%) 1.385 ops/ms [Average]
  (min, avg, max) = (9.644, 9.729, 9.790), stdev = 0.076
  CI (99.9%): [8.344, 11.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.203 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 8.989 ops/ms
Iteration   1: 9.400 ops/ms
Iteration   2: 9.438 ops/ms
Iteration   3: 9.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.374 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (9.284, 9.374, 9.438), stdev = 0.080
  CI (99.9%): [7.913, 10.835] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.677 ops/ms
# Warmup Iteration   2: 7.377 ops/ms
# Warmup Iteration   3: 7.912 ops/ms
Iteration   1: 8.213 ops/ms
Iteration   2: 8.036 ops/ms
Iteration   3: 8.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.138 ±(99.9%) 1.670 ops/ms [Average]
  (min, avg, max) = (8.036, 8.138, 8.213), stdev = 0.092
  CI (99.9%): [6.468, 9.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.841 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.588 ±(99.9%) 0.008 ms/op
Iteration   1: 3.318 ±(99.9%) 0.010 ms/op
Iteration   2: 3.430 ±(99.9%) 0.005 ms/op
Iteration   3: 3.399 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.382 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.318, 3.382, 3.430), stdev = 0.058
  CI (99.9%): [2.330, 4.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.667 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.006 ms/op
Iteration   1: 3.230 ±(99.9%) 0.011 ms/op
Iteration   2: 3.254 ±(99.9%) 0.009 ms/op
Iteration   3: 3.197 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.227 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.197, 3.227, 3.254), stdev = 0.029
  CI (99.9%): [2.707, 3.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.191 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.006 ms/op
Iteration   1: 3.301 ±(99.9%) 0.010 ms/op
Iteration   2: 3.403 ±(99.9%) 0.004 ms/op
Iteration   3: 3.467 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.390 ±(99.9%) 1.532 ms/op [Average]
  (min, avg, max) = (3.301, 3.390, 3.467), stdev = 0.084
  CI (99.9%): [1.859, 4.922] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.883 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.015 ms/op
Iteration   2: 4.051 ±(99.9%) 0.006 ms/op
Iteration   3: 3.842 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.924 ±(99.9%) 2.031 ms/op [Average]
  (min, avg, max) = (3.842, 3.924, 4.051), stdev = 0.111
  CI (99.9%): [1.893, 5.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.788 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.608 ±(99.9%) 0.012 ms/op
Iteration   1: 3.372 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  20.817 ms/op
                 createUser·p0.9999: 25.463 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.433 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.510 ms/op
                 createUser·p0.999:  22.306 ms/op
                 createUser·p0.9999: 25.287 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   3: 3.468 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  17.727 ms/op
                 createUser·p0.9999: 25.308 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280204
  mean =      3.424 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13336 
    [ 2.500,  5.000) = 261124 
    [ 5.000,  7.500) = 4806 
    [ 7.500, 10.000) = 405 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 159 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     18.114 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     26.428 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.070 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.008 ms/op
Iteration   1: 3.232 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.859 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 22.580 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.126 ms/op
                 existUser·p0.999:  17.281 ms/op
                 existUser·p0.9999: 23.517 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   3: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  17.112 ms/op
                 existUser·p0.9999: 25.495 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291538
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20254 
    [ 2.500,  5.000) = 266695 
    [ 5.000,  7.500) = 3684 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     15.222 ms/op
     p(99.9900) =     24.674 ms/op
     p(99.9990) =     25.857 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.489 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.010 ms/op
Iteration   1: 3.549 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.466 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  13.042 ms/op
                 getUser·p0.9999: 22.417 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.478 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  18.680 ms/op
                 getUser·p0.9999: 24.878 ms/op
                 getUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274363
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3544 
    [ 2.500,  5.000) = 263546 
    [ 5.000,  7.500) = 5276 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     17.847 ms/op
     p(99.9900) =     24.201 ms/op
     p(99.9990) =     25.765 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.343 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.540 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.014 ms/op
Iteration   1: 4.156 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  20.709 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  16.255 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 17.586 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238931
  mean =      4.013 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 229754 
    [ 5.000,  7.500) = 6610 
    [ 7.500, 10.000) = 1716 
    [10.000, 12.500) = 341 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     16.254 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     24.290 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.420 ± 2.873  ops/ms
ClientPb.existUser                       thrpt       3   9.729 ± 1.385  ops/ms
ClientPb.getUser                         thrpt       3   9.374 ± 1.461  ops/ms
ClientPb.listUser                        thrpt       3   8.138 ± 1.670  ops/ms
ClientPb.createUser                       avgt       3   3.382 ± 1.052   ms/op
ClientPb.existUser                        avgt       3   3.227 ± 0.520   ms/op
ClientPb.getUser                          avgt       3   3.390 ± 1.532   ms/op
ClientPb.listUser                         avgt       3   3.924 ± 2.031   ms/op
ClientPb.createUser                     sample  280204   3.424 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.784           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.114           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.330           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.427           ms/op
ClientPb.existUser                      sample  291538   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.491           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.571           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.674           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.525           ms/op
ClientPb.getUser                        sample  274363   3.497 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.423           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.847           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.201           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  238931   4.013 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.807           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
