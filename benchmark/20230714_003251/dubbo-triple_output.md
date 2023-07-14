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
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 5.467 ops/ms
# Warmup Iteration   3: 8.442 ops/ms
Iteration   1: 8.866 ops/ms
Iteration   2: 9.009 ops/ms
Iteration   3: 9.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.017 ±(99.9%) 2.817 ops/ms [Average]
  (min, avg, max) = (8.866, 9.017, 9.175), stdev = 0.154
  CI (99.9%): [6.200, 11.834] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.867 ops/ms
# Warmup Iteration   2: 8.322 ops/ms
# Warmup Iteration   3: 9.523 ops/ms
Iteration   1: 9.596 ops/ms
Iteration   2: 9.992 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.781 ±(99.9%) 3.632 ops/ms [Average]
  (min, avg, max) = (9.596, 9.781, 9.992), stdev = 0.199
  CI (99.9%): [6.149, 13.413] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.636 ops/ms
# Warmup Iteration   2: 8.554 ops/ms
# Warmup Iteration   3: 9.117 ops/ms
Iteration   1: 9.580 ops/ms
Iteration   2: 9.501 ops/ms
Iteration   3: 9.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.503 ±(99.9%) 1.386 ops/ms [Average]
  (min, avg, max) = (9.428, 9.503, 9.580), stdev = 0.076
  CI (99.9%): [8.118, 10.889] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ops/ms
# Warmup Iteration   2: 7.373 ops/ms
# Warmup Iteration   3: 7.741 ops/ms
Iteration   1: 7.847 ops/ms
Iteration   2: 7.809 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.846 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (7.809, 7.846, 7.881), stdev = 0.036
  CI (99.9%): [7.190, 8.502] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.286 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.697 ±(99.9%) 0.007 ms/op
Iteration   1: 3.472 ±(99.9%) 0.015 ms/op
Iteration   2: 3.589 ±(99.9%) 0.010 ms/op
Iteration   3: 3.517 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.526 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (3.472, 3.526, 3.589), stdev = 0.059
  CI (99.9%): [2.450, 4.602] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.003 ms/op
Iteration   1: 3.347 ±(99.9%) 0.004 ms/op
Iteration   2: 3.419 ±(99.9%) 0.008 ms/op
Iteration   3: 3.483 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.416 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.347, 3.416, 3.483), stdev = 0.068
  CI (99.9%): [2.177, 4.656] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.287 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.006 ms/op
Iteration   1: 3.347 ±(99.9%) 0.010 ms/op
Iteration   2: 3.412 ±(99.9%) 0.007 ms/op
Iteration   3: 3.342 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.367 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (3.342, 3.367, 3.412), stdev = 0.039
  CI (99.9%): [2.648, 4.086] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.185 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.077 ±(99.9%) 0.010 ms/op
Iteration   1: 3.992 ±(99.9%) 0.009 ms/op
Iteration   2: 3.912 ±(99.9%) 0.013 ms/op
Iteration   3: 3.900 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.935 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.900, 3.935, 3.992), stdev = 0.050
  CI (99.9%): [3.027, 4.842] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.293 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.010 ms/op
Iteration   1: 3.451 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  19.229 ms/op
                 createUser·p0.9999: 21.594 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 24.718 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   3: 3.609 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  20.406 ms/op
                 createUser·p0.9999: 25.334 ms/op
                 createUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273432
  mean =      3.508 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4929 
    [ 2.500,  5.000) = 262543 
    [ 5.000,  7.500) = 4787 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 176 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     24.805 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.680 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.007 ms/op
Iteration   1: 3.376 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.809 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  19.013 ms/op
                 existUser·p0.9999: 22.186 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  21.211 ms/op
                 existUser·p0.9999: 25.775 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.295 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 25.966 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287975
  mean =      3.332 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9588 
    [ 2.500,  5.000) = 272199 
    [ 5.000,  7.500) = 5263 
    [ 7.500, 10.000) = 515 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     14.615 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     26.779 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 9.136 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
Iteration   1: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.923 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  20.513 ms/op
                 getUser·p0.9999: 23.227 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.561 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.366 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  22.190 ms/op
                 getUser·p0.9999: 28.213 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 3.580 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  23.156 ms/op
                 getUser·p0.9999: 27.986 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270824
  mean =      3.544 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6736 
    [ 2.500,  5.000) = 255200 
    [ 5.000,  7.500) = 7747 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     20.944 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     28.527 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 10.291 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.015 ms/op
Iteration   1: 4.132 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   7.912 ms/op
                 listUser·p0.999:  17.733 ms/op
                 listUser·p0.9999: 31.131 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 3.937 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  14.381 ms/op
                 listUser·p0.9999: 16.138 ms/op
                 listUser·p1.00:   16.400 ms/op

Iteration   3: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237969
  mean =      4.030 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 228561 
    [ 5.000,  7.500) = 7036 
    [ 7.500, 10.000) = 1652 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.457 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     30.015 ms/op
     p(99.9990) =     31.690 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.017 ± 2.817  ops/ms
ClientPb.existUser                       thrpt       3   9.781 ± 3.632  ops/ms
ClientPb.getUser                         thrpt       3   9.503 ± 1.386  ops/ms
ClientPb.listUser                        thrpt       3   7.846 ± 0.656  ops/ms
ClientPb.createUser                       avgt       3   3.526 ± 1.076   ms/op
ClientPb.existUser                        avgt       3   3.416 ± 1.239   ms/op
ClientPb.getUser                          avgt       3   3.367 ± 0.719   ms/op
ClientPb.listUser                         avgt       3   3.935 ± 0.908   ms/op
ClientPb.createUser                     sample  273432   3.508 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.128           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.437           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.120           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.805           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.903           ms/op
ClientPb.existUser                      sample  287975   3.332 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.456           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.615           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.559           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.870           ms/op
ClientPb.getUser                        sample  270824   3.544 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.317           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.944           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.820           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  237969   4.030 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.457           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.015           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.342           ms/op
