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
# Warmup Iteration   1: 1.037 ops/ms
# Warmup Iteration   2: 2.211 ops/ms
# Warmup Iteration   3: 4.881 ops/ms
Iteration   1: 5.477 ops/ms
Iteration   2: 5.507 ops/ms
Iteration   3: 5.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.660 ±(99.9%) 5.307 ops/ms [Average]
  (min, avg, max) = (5.477, 5.660, 5.995), stdev = 0.291
  CI (99.9%): [0.352, 10.967] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.512 ops/ms
# Warmup Iteration   2: 4.167 ops/ms
# Warmup Iteration   3: 5.880 ops/ms
Iteration   1: 6.059 ops/ms
Iteration   2: 5.897 ops/ms
Iteration   3: 5.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.961 ±(99.9%) 1.571 ops/ms [Average]
  (min, avg, max) = (5.897, 5.961, 6.059), stdev = 0.086
  CI (99.9%): [4.390, 7.531] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.450 ops/ms
# Warmup Iteration   2: 3.862 ops/ms
# Warmup Iteration   3: 5.552 ops/ms
Iteration   1: 5.447 ops/ms
Iteration   2: 5.726 ops/ms
Iteration   3: 5.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.627 ±(99.9%) 2.855 ops/ms [Average]
  (min, avg, max) = (5.447, 5.627, 5.726), stdev = 0.156
  CI (99.9%): [2.772, 8.482] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.459 ops/ms
# Warmup Iteration   2: 3.803 ops/ms
# Warmup Iteration   3: 4.650 ops/ms
Iteration   1: 4.868 ops/ms
Iteration   2: 4.967 ops/ms
Iteration   3: 4.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.908 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (4.868, 4.908, 4.967), stdev = 0.052
  CI (99.9%): [3.956, 5.859] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 17.901 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.610 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.000 ±(99.9%) 0.007 ms/op
Iteration   1: 5.765 ±(99.9%) 0.010 ms/op
Iteration   2: 5.528 ±(99.9%) 0.018 ms/op
Iteration   3: 5.432 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.575 ±(99.9%) 3.119 ms/op [Average]
  (min, avg, max) = (5.432, 5.575, 5.765), stdev = 0.171
  CI (99.9%): [2.456, 8.694] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.795 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 6.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.606 ±(99.9%) 0.011 ms/op
Iteration   1: 5.301 ±(99.9%) 0.011 ms/op
Iteration   2: 5.261 ±(99.9%) 0.015 ms/op
Iteration   3: 5.211 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.258 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (5.211, 5.258, 5.301), stdev = 0.045
  CI (99.9%): [4.432, 6.083] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.197 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.993 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.013 ms/op
Iteration   1: 5.585 ±(99.9%) 0.015 ms/op
Iteration   2: 5.363 ±(99.9%) 0.016 ms/op
Iteration   3: 5.352 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.433 ±(99.9%) 2.392 ms/op [Average]
  (min, avg, max) = (5.352, 5.433, 5.585), stdev = 0.131
  CI (99.9%): [3.042, 7.825] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.671 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 8.312 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.652 ±(99.9%) 0.021 ms/op
Iteration   1: 6.557 ±(99.9%) 0.016 ms/op
Iteration   2: 6.484 ±(99.9%) 0.014 ms/op
Iteration   3: 6.367 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.469 ±(99.9%) 1.752 ms/op [Average]
  (min, avg, max) = (6.367, 6.469, 6.557), stdev = 0.096
  CI (99.9%): [4.717, 8.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 20.820 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 7.340 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.611 ±(99.9%) 0.035 ms/op
Iteration   1: 5.656 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.897 ms/op
                 createUser·p0.99:   11.485 ms/op
                 createUser·p0.999:  18.067 ms/op
                 createUser·p0.9999: 32.191 ms/op
                 createUser·p1.00:   32.735 ms/op

Iteration   2: 6.309 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.726 ms/op
                 createUser·p0.90:   8.618 ms/op
                 createUser·p0.95:   9.994 ms/op
                 createUser·p0.99:   13.235 ms/op
                 createUser·p0.999:  25.863 ms/op
                 createUser·p0.9999: 38.858 ms/op
                 createUser·p1.00:   40.894 ms/op

Iteration   3: 6.124 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   5.579 ms/op
                 createUser·p0.90:   8.290 ms/op
                 createUser·p0.95:   9.863 ms/op
                 createUser·p0.99:   13.287 ms/op
                 createUser·p0.999:  31.802 ms/op
                 createUser·p0.9999: 35.223 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159404
  mean =      6.017 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 33638 
    [ 5.000, 10.000) = 119582 
    [10.000, 15.000) = 5590 
    [15.000, 20.000) = 396 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 102 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.938 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.681 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     40.817 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.424 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.544 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.574 ±(99.9%) 0.022 ms/op
Iteration   1: 5.762 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.976 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.733 ms/op
                 existUser·p0.99:   11.583 ms/op
                 existUser·p0.999:  17.318 ms/op
                 existUser·p0.9999: 27.089 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   2: 5.554 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.767 ms/op
                 existUser·p0.95:   7.741 ms/op
                 existUser·p0.99:   11.390 ms/op
                 existUser·p0.999:  27.441 ms/op
                 existUser·p0.9999: 29.860 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   3: 5.072 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.595 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  14.443 ms/op
                 existUser·p0.9999: 37.073 ms/op
                 existUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176150
  mean =      5.447 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 76319 
    [ 5.000,  7.500) = 89535 
    [ 7.500, 10.000) = 7419 
    [10.000, 12.500) = 1965 
    [12.500, 15.000) = 545 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.791 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     16.926 ms/op
     p(99.9900) =     36.327 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.087 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 7.187 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.719 ±(99.9%) 0.022 ms/op
Iteration   1: 5.552 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.520 ms/op
                 getUser·p0.99:   10.708 ms/op
                 getUser·p0.999:  19.952 ms/op
                 getUser·p0.9999: 28.483 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 5.660 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   3.015 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.692 ms/op
                 getUser·p0.99:   10.404 ms/op
                 getUser·p0.999:  26.931 ms/op
                 getUser·p0.9999: 36.372 ms/op
                 getUser·p1.00:   36.766 ms/op

Iteration   3: 5.602 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.781 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   7.487 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  32.375 ms/op
                 getUser·p0.9999: 40.081 ms/op
                 getUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171261
  mean =      5.604 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45564 
    [ 5.000, 10.000) = 123429 
    [10.000, 15.000) = 1907 
    [15.000, 20.000) = 170 
    [20.000, 25.000) = 35 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.621 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.561 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     20.406 ms/op
     p(99.9900) =     38.388 ms/op
     p(99.9990) =     40.473 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.499 ±(99.9%) 0.380 ms/op
# Warmup Iteration   2: 7.493 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.400 ±(99.9%) 0.026 ms/op
Iteration   1: 6.316 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.225 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  27.841 ms/op
                 listUser·p0.9999: 30.931 ms/op
                 listUser·p1.00:   32.539 ms/op

Iteration   2: 6.647 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.986 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   7.561 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  32.831 ms/op
                 listUser·p0.9999: 38.542 ms/op
                 listUser·p1.00:   39.059 ms/op

Iteration   3: 6.539 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.703 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.502 ms/op
                 listUser·p0.999:  26.221 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147745
  mean =      6.498 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 3730 
    [ 5.000,  7.500) = 128811 
    [ 7.500, 10.000) = 11307 
    [10.000, 12.500) = 2901 
    [12.500, 15.000) = 552 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.490 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      7.528 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     28.295 ms/op
     p(99.9900) =     37.239 ms/op
     p(99.9990) =     39.028 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.660 ± 5.307  ops/ms
ClientPb.existUser                       thrpt       3   5.961 ± 1.571  ops/ms
ClientPb.getUser                         thrpt       3   5.627 ± 2.855  ops/ms
ClientPb.listUser                        thrpt       3   4.908 ± 0.952  ops/ms
ClientPb.createUser                       avgt       3   5.575 ± 3.119   ms/op
ClientPb.existUser                        avgt       3   5.258 ± 0.826   ms/op
ClientPb.getUser                          avgt       3   5.433 ± 2.392   ms/op
ClientPb.listUser                         avgt       3   6.469 ± 1.752   ms/op
ClientPb.createUser                     sample  159404   6.017 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.317           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.938           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.454           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.681           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.805           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.438           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.894           ms/op
ClientPb.existUser                      sample  176150   5.447 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.948           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.112           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.791           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.961           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.327           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.290           ms/op
ClientPb.getUser                        sample  171261   5.604 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.621           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.650           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.406           ms/op
ClientPb.getUser:getUser·p0.9999        sample          38.388           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.567           ms/op
ClientPb.listUser                       sample  147745   6.498 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.490           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.665           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.295           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.239           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.059           ms/op
