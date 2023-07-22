# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.349 ops/ms
# Warmup Iteration   2: 3.814 ops/ms
# Warmup Iteration   3: 6.386 ops/ms
Iteration   1: 6.523 ops/ms
Iteration   2: 6.846 ops/ms
Iteration   3: 6.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.663 ±(99.9%) 3.029 ops/ms [Average]
  (min, avg, max) = (6.523, 6.663, 6.846), stdev = 0.166
  CI (99.9%): [3.633, 9.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.862 ops/ms
# Warmup Iteration   2: 6.068 ops/ms
# Warmup Iteration   3: 6.648 ops/ms
Iteration   1: 6.995 ops/ms
Iteration   2: 7.038 ops/ms
Iteration   3: 6.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.988 ±(99.9%) 0.968 ops/ms [Average]
  (min, avg, max) = (6.932, 6.988, 7.038), stdev = 0.053
  CI (99.9%): [6.021, 7.956] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.004 ops/ms
# Warmup Iteration   2: 5.918 ops/ms
# Warmup Iteration   3: 6.333 ops/ms
Iteration   1: 6.735 ops/ms
Iteration   2: 6.882 ops/ms
Iteration   3: 6.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.711 ±(99.9%) 3.360 ops/ms [Average]
  (min, avg, max) = (6.516, 6.711, 6.882), stdev = 0.184
  CI (99.9%): [3.352, 10.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 1.960 ops/ms
# Warmup Iteration   2: 5.104 ops/ms
# Warmup Iteration   3: 5.609 ops/ms
Iteration   1: 5.694 ops/ms
Iteration   2: 5.924 ops/ms
Iteration   3: 5.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.746 ±(99.9%) 2.878 ops/ms [Average]
  (min, avg, max) = (5.621, 5.746, 5.924), stdev = 0.158
  CI (99.9%): [2.869, 8.624] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.354 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.379 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.044 ±(99.9%) 0.009 ms/op
Iteration   1: 4.952 ±(99.9%) 0.009 ms/op
Iteration   2: 5.040 ±(99.9%) 0.008 ms/op
Iteration   3: 4.833 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.942 ±(99.9%) 1.890 ms/op [Average]
  (min, avg, max) = (4.833, 4.942, 5.040), stdev = 0.104
  CI (99.9%): [3.052, 6.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 13.165 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.020 ms/op
Iteration   1: 4.546 ±(99.9%) 0.008 ms/op
Iteration   2: 4.385 ±(99.9%) 0.013 ms/op
Iteration   3: 4.524 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.485 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (4.385, 4.485, 4.546), stdev = 0.087
  CI (99.9%): [2.889, 6.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.400 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.425 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.009 ms/op
Iteration   1: 4.803 ±(99.9%) 0.009 ms/op
Iteration   2: 4.850 ±(99.9%) 0.009 ms/op
Iteration   3: 5.049 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.901 ±(99.9%) 2.379 ms/op [Average]
  (min, avg, max) = (4.803, 4.901, 5.049), stdev = 0.130
  CI (99.9%): [2.521, 7.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.369 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.920 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.492 ±(99.9%) 0.017 ms/op
Iteration   1: 5.375 ±(99.9%) 0.017 ms/op
Iteration   2: 5.442 ±(99.9%) 0.019 ms/op
Iteration   3: 5.527 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.448 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (5.375, 5.448, 5.527), stdev = 0.076
  CI (99.9%): [4.063, 6.833] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.666 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.730 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.324 ±(99.9%) 0.022 ms/op
Iteration   1: 4.762 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.363 ms/op
                 createUser·p0.50:   4.563 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.291 ms/op
                 createUser·p0.99:   8.626 ms/op
                 createUser·p0.999:  12.793 ms/op
                 createUser·p0.9999: 22.703 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 4.854 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.423 ms/op
                 createUser·p0.99:   8.831 ms/op
                 createUser·p0.999:  18.882 ms/op
                 createUser·p0.9999: 27.130 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   3: 4.953 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   6.627 ms/op
                 createUser·p0.99:   8.364 ms/op
                 createUser·p0.999:  20.412 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 197578
  mean =      4.855 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 138664 
    [ 5.000,  7.500) = 54956 
    [ 7.500, 10.000) = 3124 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     18.364 ms/op
     p(99.9900) =     28.237 ms/op
     p(99.9990) =     30.115 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.033 ±(99.9%) 0.210 ms/op
# Warmup Iteration   2: 5.327 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.732 ±(99.9%) 0.016 ms/op
Iteration   1: 4.676 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.751 ms/op
                 existUser·p0.95:   6.545 ms/op
                 existUser·p0.99:   8.897 ms/op
                 existUser·p0.999:  21.660 ms/op
                 existUser·p0.9999: 26.384 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 4.617 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.480 ms/op
                 existUser·p0.95:   6.373 ms/op
                 existUser·p0.99:   9.208 ms/op
                 existUser·p0.999:  16.047 ms/op
                 existUser·p0.9999: 26.643 ms/op
                 existUser·p1.00:   27.427 ms/op

Iteration   3: 4.571 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.085 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.472 ms/op
                 existUser·p0.95:   6.177 ms/op
                 existUser·p0.99:   8.098 ms/op
                 existUser·p0.999:  15.205 ms/op
                 existUser·p0.9999: 27.263 ms/op
                 existUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 207600
  mean =      4.621 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 169628 
    [ 5.000,  7.500) = 33461 
    [ 7.500, 10.000) = 3176 
    [10.000, 12.500) = 747 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.587 ms/op
     p(95.0000) =      6.341 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     21.122 ms/op
     p(99.9900) =     26.705 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.685 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 5.823 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.167 ±(99.9%) 0.017 ms/op
Iteration   1: 4.781 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   5.661 ms/op
                 getUser·p0.95:   6.521 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  14.763 ms/op
                 getUser·p0.9999: 23.960 ms/op
                 getUser·p1.00:   24.543 ms/op

Iteration   2: 4.842 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  15.185 ms/op
                 getUser·p0.9999: 29.941 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   3: 4.855 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   4.588 ms/op
                 getUser·p0.90:   5.947 ms/op
                 getUser·p0.95:   6.496 ms/op
                 getUser·p0.99:   8.266 ms/op
                 getUser·p0.999:  23.477 ms/op
                 getUser·p0.9999: 27.080 ms/op
                 getUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 198891
  mean =      4.826 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 143829 
    [ 5.000,  7.500) = 50421 
    [ 7.500, 10.000) = 3658 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.775 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     21.663 ms/op
     p(99.9900) =     27.467 ms/op
     p(99.9990) =     33.066 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.311 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.030 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.963 ±(99.9%) 0.023 ms/op
Iteration   1: 5.650 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.799 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  23.801 ms/op
                 listUser·p0.9999: 27.929 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 5.758 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.830 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  24.904 ms/op
                 listUser·p0.9999: 28.359 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   3: 5.658 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.879 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   6.406 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  18.977 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 168565
  mean =      5.688 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 33054 
    [ 5.000,  7.500) = 126970 
    [ 7.500, 10.000) = 6617 
    [10.000, 12.500) = 1034 
    [12.500, 15.000) = 395 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.548 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.512 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     22.559 ms/op
     p(99.9900) =     28.054 ms/op
     p(99.9990) =     29.936 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.663 ± 3.029  ops/ms
ClientPb.existUser                       thrpt       3   6.988 ± 0.968  ops/ms
ClientPb.getUser                         thrpt       3   6.711 ± 3.360  ops/ms
ClientPb.listUser                        thrpt       3   5.746 ± 2.878  ops/ms
ClientPb.createUser                       avgt       3   4.942 ± 1.890   ms/op
ClientPb.existUser                        avgt       3   4.485 ± 1.596   ms/op
ClientPb.getUser                          avgt       3   4.901 ± 2.379   ms/op
ClientPb.listUser                         avgt       3   5.448 ± 1.385   ms/op
ClientPb.createUser                     sample  197578   4.855 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.195           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.569           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.364           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.237           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  207600   4.621 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.454           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.341           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.122           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  198891   4.826 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.693           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.602           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.663           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.467           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.325           ms/op
ClientPb.listUser                       sample  168565   5.688 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.322           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.559           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.054           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
