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
# Warmup Iteration   1: 2.054 ops/ms
# Warmup Iteration   2: 4.846 ops/ms
# Warmup Iteration   3: 8.456 ops/ms
Iteration   1: 9.517 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.433 ±(99.9%) 2.606 ops/ms [Average]
  (min, avg, max) = (9.268, 9.433, 9.517), stdev = 0.143
  CI (99.9%): [6.827, 12.038] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.869 ops/ms
# Warmup Iteration   2: 8.389 ops/ms
# Warmup Iteration   3: 9.535 ops/ms
Iteration   1: 9.599 ops/ms
Iteration   2: 9.541 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.651 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (9.541, 9.651, 9.812), stdev = 0.143
  CI (99.9%): [7.049, 12.253] (assumes normal distribution)


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
# Warmup Iteration   1: 2.747 ops/ms
# Warmup Iteration   2: 8.280 ops/ms
# Warmup Iteration   3: 9.023 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.447 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.339 ±(99.9%) 2.008 ops/ms [Average]
  (min, avg, max) = (9.227, 9.339, 9.447), stdev = 0.110
  CI (99.9%): [7.331, 11.347] (assumes normal distribution)


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
# Warmup Iteration   1: 3.055 ops/ms
# Warmup Iteration   2: 7.098 ops/ms
# Warmup Iteration   3: 7.764 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 8.291 ops/ms
Iteration   3: 8.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.117 ±(99.9%) 2.861 ops/ms [Average]
  (min, avg, max) = (7.985, 8.117, 8.291), stdev = 0.157
  CI (99.9%): [5.256, 10.979] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.109 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.207 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.004 ms/op
Iteration   1: 3.432 ±(99.9%) 0.009 ms/op
Iteration   2: 3.424 ±(99.9%) 0.008 ms/op
Iteration   3: 3.472 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.443 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.424, 3.443, 3.472), stdev = 0.026
  CI (99.9%): [2.972, 3.914] (assumes normal distribution)


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
# Warmup Iteration   1: 8.482 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.012 ms/op
Iteration   1: 3.325 ±(99.9%) 0.002 ms/op
Iteration   2: 3.268 ±(99.9%) 0.006 ms/op
Iteration   3: 3.314 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.302 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.268, 3.302, 3.325), stdev = 0.030
  CI (99.9%): [2.757, 3.848] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.723 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.004 ms/op
Iteration   1: 3.497 ±(99.9%) 0.004 ms/op
Iteration   2: 3.557 ±(99.9%) 0.005 ms/op
Iteration   3: 3.444 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.499 ±(99.9%) 1.032 ms/op [Average]
  (min, avg, max) = (3.444, 3.499, 3.557), stdev = 0.057
  CI (99.9%): [2.468, 4.531] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.825 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.999 ±(99.9%) 0.009 ms/op
Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
Iteration   3: 4.033 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.031 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.999, 4.031, 4.061), stdev = 0.031
  CI (99.9%): [3.457, 4.605] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.305 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.011 ms/op
Iteration   1: 3.601 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   3.353 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.881 ms/op
                 createUser·p0.999:  13.277 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.374 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.444 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  16.204 ms/op
                 createUser·p0.9999: 24.163 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276596
  mean =      3.471 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7075 
    [ 2.500,  5.000) = 260648 
    [ 5.000,  7.500) = 6859 
    [ 7.500, 10.000) = 1378 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     15.955 ms/op
     p(99.9900) =     22.752 ms/op
     p(99.9990) =     25.474 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 8.780 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
Iteration   1: 3.276 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.224 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  10.204 ms/op
                 existUser·p0.9999: 23.462 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.239 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  17.760 ms/op
                 existUser·p0.9999: 25.240 ms/op
                 existUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295485
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10682 
    [ 2.500,  5.000) = 280912 
    [ 5.000,  7.500) = 3114 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     14.918 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     26.414 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 9.955 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.706 ±(99.9%) 0.012 ms/op
Iteration   1: 3.535 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  19.738 ms/op
                 getUser·p0.9999: 26.141 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 3.561 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.436 ms/op
                 getUser·p0.999:  22.583 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 27.779 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273013
  mean =      3.517 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6660 
    [ 2.500,  5.000) = 256894 
    [ 5.000,  7.500) = 7951 
    [ 7.500, 10.000) = 975 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     15.152 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.939 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 10.184 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.015 ms/op
Iteration   1: 4.207 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.016 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 22.924 ms/op
                 listUser·p1.00:   23.921 ms/op

Iteration   2: 4.064 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   8.033 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.898 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 18.376 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236700
  mean =      4.053 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 226847 
    [ 5.000,  7.500) = 7216 
    [ 7.500, 10.000) = 1589 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.688 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.433 ± 2.606  ops/ms
ClientPb.existUser                       thrpt       3   9.651 ± 2.602  ops/ms
ClientPb.getUser                         thrpt       3   9.339 ± 2.008  ops/ms
ClientPb.listUser                        thrpt       3   8.117 ± 2.861  ops/ms
ClientPb.createUser                       avgt       3   3.443 ± 0.471   ms/op
ClientPb.existUser                        avgt       3   3.302 ± 0.546   ms/op
ClientPb.getUser                          avgt       3   3.499 ± 1.032   ms/op
ClientPb.listUser                         avgt       3   4.031 ± 0.574   ms/op
ClientPb.createUser                     sample  276596   3.471 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.319           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.209           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.955           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.752           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.690           ms/op
ClientPb.existUser                      sample  295485   3.246 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.187           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.918           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.150           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  273013   3.517 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.849           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.152           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.853           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  236700   4.053 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.941           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.217           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.921           ms/op
