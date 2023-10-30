# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.517 ops/ms
# Warmup Iteration   2: 3.075 ops/ms
# Warmup Iteration   3: 6.676 ops/ms
Iteration   1: 7.303 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 7.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.661 ±(99.9%) 5.716 ops/ms [Average]
  (min, avg, max) = (7.303, 7.661, 7.884), stdev = 0.313
  CI (99.9%): [1.945, 13.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.244 ops/ms
# Warmup Iteration   2: 7.113 ops/ms
# Warmup Iteration   3: 7.692 ops/ms
Iteration   1: 8.434 ops/ms
Iteration   2: 8.219 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.237 ±(99.9%) 3.428 ops/ms [Average]
  (min, avg, max) = (8.060, 8.237, 8.434), stdev = 0.188
  CI (99.9%): [4.809, 11.666] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.196 ops/ms
# Warmup Iteration   2: 6.316 ops/ms
# Warmup Iteration   3: 7.651 ops/ms
Iteration   1: 8.011 ops/ms
Iteration   2: 8.042 ops/ms
Iteration   3: 8.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.039 ±(99.9%) 0.498 ops/ms [Average]
  (min, avg, max) = (8.011, 8.039, 8.065), stdev = 0.027
  CI (99.9%): [7.541, 8.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 6.015 ops/ms
# Warmup Iteration   3: 6.497 ops/ms
Iteration   1: 6.469 ops/ms
Iteration   2: 6.625 ops/ms
Iteration   3: 6.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.639 ±(99.9%) 3.227 ops/ms [Average]
  (min, avg, max) = (6.469, 6.639, 6.822), stdev = 0.177
  CI (99.9%): [3.412, 9.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.177 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.159 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.004 ms/op
Iteration   1: 4.079 ±(99.9%) 0.005 ms/op
Iteration   2: 4.140 ±(99.9%) 0.004 ms/op
Iteration   3: 3.911 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.043 ±(99.9%) 2.165 ms/op [Average]
  (min, avg, max) = (3.911, 4.043, 4.140), stdev = 0.119
  CI (99.9%): [1.878, 6.209] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.689 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.003 ms/op
Iteration   1: 3.907 ±(99.9%) 0.004 ms/op
Iteration   2: 3.765 ±(99.9%) 0.003 ms/op
Iteration   3: 3.877 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.850 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.765, 3.850, 3.907), stdev = 0.075
  CI (99.9%): [2.487, 5.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.686 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.003 ms/op
Iteration   1: 4.090 ±(99.9%) 0.003 ms/op
Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
Iteration   3: 3.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.028 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.994, 4.028, 4.090), stdev = 0.054
  CI (99.9%): [3.040, 5.016] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.362 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.790 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.998 ±(99.9%) 0.008 ms/op
Iteration   1: 4.764 ±(99.9%) 0.007 ms/op
Iteration   2: 4.827 ±(99.9%) 0.006 ms/op
Iteration   3: 4.717 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.769 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (4.717, 4.769, 4.827), stdev = 0.055
  CI (99.9%): [3.766, 5.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.611 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.848 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.447 ±(99.9%) 0.019 ms/op
Iteration   1: 4.159 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   7.910 ms/op
                 createUser·p0.999:  21.006 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.780 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.741 ms/op
                 createUser·p0.999:  16.089 ms/op
                 createUser·p0.9999: 26.344 ms/op
                 createUser·p1.00:   27.558 ms/op

Iteration   3: 3.996 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.858 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.840 ms/op
                 createUser·p0.999:  27.360 ms/op
                 createUser·p0.9999: 29.883 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237077
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 564 
    [ 2.500,  5.000) = 223762 
    [ 5.000,  7.500) = 10293 
    [ 7.500, 10.000) = 1527 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     21.854 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     30.134 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.312 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   7.409 ms/op
                 existUser·p0.999:  26.059 ms/op
                 existUser·p0.9999: 28.583 ms/op
                 existUser·p1.00:   29.884 ms/op

Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   7.529 ms/op
                 existUser·p0.999:  16.458 ms/op
                 existUser·p0.9999: 32.138 ms/op
                 existUser·p1.00:   33.391 ms/op

Iteration   3: 3.884 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.913 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   7.833 ms/op
                 existUser·p0.999:  22.217 ms/op
                 existUser·p0.9999: 32.924 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243517
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 405 
    [ 2.500,  5.000) = 233096 
    [ 5.000,  7.500) = 7413 
    [ 7.500, 10.000) = 1843 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     22.200 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.801 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.301 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.183 ±(99.9%) 0.012 ms/op
Iteration   1: 4.048 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.702 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  24.150 ms/op
                 getUser·p0.9999: 27.135 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.269 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.666 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 27.946 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 4.002 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  28.544 ms/op
                 getUser·p0.9999: 32.178 ms/op
                 getUser·p1.00:   33.096 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239550
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179 
    [ 2.500,  5.000) = 228397 
    [ 5.000,  7.500) = 8504 
    [ 7.500, 10.000) = 1741 
    [10.000, 12.500) = 297 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     23.346 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     32.750 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.541 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.873 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.016 ms/op
Iteration   1: 4.761 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  26.051 ms/op
                 listUser·p0.9999: 29.218 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   2: 4.946 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   5.460 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   9.397 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 26.479 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   3: 4.813 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 19.684 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198093
  mean =      4.839 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 151435 
    [ 5.000,  7.500) = 41540 
    [ 7.500, 10.000) = 3809 
    [10.000, 12.500) = 574 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     20.379 ms/op
     p(99.9900) =     27.833 ms/op
     p(99.9990) =     30.389 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.661 ± 5.716  ops/ms
ClientPb.existUser                       thrpt       3   8.237 ± 3.428  ops/ms
ClientPb.getUser                         thrpt       3   8.039 ± 0.498  ops/ms
ClientPb.listUser                        thrpt       3   6.639 ± 3.227  ops/ms
ClientPb.createUser                       avgt       3   4.043 ± 2.165   ms/op
ClientPb.existUser                        avgt       3   3.850 ± 1.363   ms/op
ClientPb.getUser                          avgt       3   4.028 ± 0.988   ms/op
ClientPb.listUser                         avgt       3   4.769 ± 1.004   ms/op
ClientPb.createUser                     sample  237077   4.050 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.350           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.854           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.179           ms/op
ClientPb.existUser                      sample  243517   3.939 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.635           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.145           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  239550   4.009 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.346           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.130           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.096           ms/op
ClientPb.listUser                       sample  198093   4.839 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.741           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.374           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.379           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.833           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.064           ms/op
