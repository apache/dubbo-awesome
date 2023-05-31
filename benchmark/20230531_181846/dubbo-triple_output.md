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
# Warmup Iteration   1: 1.976 ops/ms
# Warmup Iteration   2: 5.120 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.169 ops/ms
Iteration   3: 9.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.261 ±(99.9%) 1.575 ops/ms [Average]
  (min, avg, max) = (9.169, 9.261, 9.340), stdev = 0.086
  CI (99.9%): [7.686, 10.835] (assumes normal distribution)


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
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 8.974 ops/ms
# Warmup Iteration   3: 9.883 ops/ms
Iteration   1: 10.104 ops/ms
Iteration   2: 9.959 ops/ms
Iteration   3: 10.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.035 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (9.959, 10.035, 10.104), stdev = 0.073
  CI (99.9%): [8.709, 11.361] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 8.140 ops/ms
# Warmup Iteration   3: 9.435 ops/ms
Iteration   1: 9.376 ops/ms
Iteration   2: 9.267 ops/ms
Iteration   3: 9.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.320 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (9.267, 9.320, 9.376), stdev = 0.055
  CI (99.9%): [8.321, 10.319] (assumes normal distribution)


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
# Warmup Iteration   1: 2.684 ops/ms
# Warmup Iteration   2: 7.090 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 7.467 ops/ms
Iteration   3: 7.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.787 ±(99.9%) 5.162 ops/ms [Average]
  (min, avg, max) = (7.467, 7.787, 8.005), stdev = 0.283
  CI (99.9%): [2.625, 12.949] (assumes normal distribution)


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
# Warmup Iteration   1: 9.952 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.006 ms/op
Iteration   1: 3.425 ±(99.9%) 0.004 ms/op
Iteration   2: 3.421 ±(99.9%) 0.004 ms/op
Iteration   3: 3.519 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.455 ±(99.9%) 1.015 ms/op [Average]
  (min, avg, max) = (3.421, 3.455, 3.519), stdev = 0.056
  CI (99.9%): [2.440, 4.470] (assumes normal distribution)


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
# Warmup Iteration   1: 8.875 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.005 ms/op
Iteration   1: 3.313 ±(99.9%) 0.007 ms/op
Iteration   2: 3.282 ±(99.9%) 0.009 ms/op
Iteration   3: 3.222 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.272 ±(99.9%) 0.837 ms/op [Average]
  (min, avg, max) = (3.222, 3.272, 3.313), stdev = 0.046
  CI (99.9%): [2.435, 4.109] (assumes normal distribution)


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
# Warmup Iteration   1: 8.420 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.005 ms/op
Iteration   1: 3.358 ±(99.9%) 0.009 ms/op
Iteration   2: 3.297 ±(99.9%) 0.005 ms/op
Iteration   3: 3.314 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.323 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.297, 3.323, 3.358), stdev = 0.032
  CI (99.9%): [2.748, 3.899] (assumes normal distribution)


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
# Warmup Iteration   1: 11.098 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.887 ±(99.9%) 0.011 ms/op
Iteration   2: 4.061 ±(99.9%) 0.010 ms/op
Iteration   3: 3.962 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.970 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.887, 3.970, 4.061), stdev = 0.087
  CI (99.9%): [2.377, 5.562] (assumes normal distribution)


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
# Warmup Iteration   1: 8.804 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.008 ms/op
Iteration   1: 3.290 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.719 ms/op
                 createUser·p0.999:  10.621 ms/op
                 createUser·p0.9999: 23.143 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.404 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  19.697 ms/op
                 createUser·p0.9999: 22.538 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.447 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.260 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  17.980 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283929
  mean =      3.379 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7922 
    [ 2.500,  5.000) = 269654 
    [ 5.000,  7.500) = 5106 
    [ 7.500, 10.000) = 753 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     18.055 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 9.719 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.258 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.532 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  10.531 ms/op
                 existUser·p0.9999: 21.966 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.490 ms/op
                 existUser·p0.999:  19.681 ms/op
                 existUser·p0.9999: 23.896 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.802 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.599 ms/op
                 existUser·p0.999:  19.048 ms/op
                 existUser·p0.9999: 24.125 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285632
  mean =      3.358 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6511 
    [ 2.500,  5.000) = 273560 
    [ 5.000,  7.500) = 4329 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     19.116 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     25.175 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 8.902 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.010 ms/op
Iteration   1: 3.529 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.479 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  21.017 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.455 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.729 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.141 ms/op
                 getUser·p0.999:  23.322 ms/op
                 getUser·p0.9999: 27.515 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 3.554 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 27.427 ms/op
                 getUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273224
  mean =      3.512 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8376 
    [ 2.500,  5.000) = 254666 
    [ 5.000,  7.500) = 8379 
    [ 7.500, 10.000) = 1169 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 98 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     21.128 ms/op
     p(99.9900) =     27.187 ms/op
     p(99.9990) =     27.980 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 11.139 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.012 ms/op
Iteration   1: 4.152 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  21.404 ms/op
                 listUser·p0.9999: 26.778 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 3.901 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 17.000 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 3.935 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.193 ms/op
                 listUser·p0.999:  14.560 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240309
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 231943 
    [ 5.000,  7.500) = 6159 
    [ 7.500, 10.000) = 1309 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     25.690 ms/op
     p(99.9990) =     27.453 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.261 ± 1.575  ops/ms
ClientPb.existUser                       thrpt       3  10.035 ± 1.326  ops/ms
ClientPb.getUser                         thrpt       3   9.320 ± 0.999  ops/ms
ClientPb.listUser                        thrpt       3   7.787 ± 5.162  ops/ms
ClientPb.createUser                       avgt       3   3.455 ± 1.015   ms/op
ClientPb.existUser                        avgt       3   3.272 ± 0.837   ms/op
ClientPb.getUser                          avgt       3   3.323 ± 0.575   ms/op
ClientPb.listUser                         avgt       3   3.970 ± 1.593   ms/op
ClientPb.createUser                     sample  283929   3.379 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.260           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.623           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.852           ms/op
ClientPb.existUser                      sample  285632   3.358 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.024           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.116           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.790           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.231           ms/op
ClientPb.getUser                        sample  273224   3.512 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.128           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.187           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.213           ms/op
ClientPb.listUser                       sample  240309   3.993 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.692           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.745           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.690           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
