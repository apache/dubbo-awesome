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
# Warmup Iteration   1: 2.042 ops/ms
# Warmup Iteration   2: 5.560 ops/ms
# Warmup Iteration   3: 8.801 ops/ms
Iteration   1: 9.133 ops/ms
Iteration   2: 8.916 ops/ms
Iteration   3: 8.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.013 ±(99.9%) 2.015 ops/ms [Average]
  (min, avg, max) = (8.916, 9.013, 9.133), stdev = 0.110
  CI (99.9%): [6.998, 11.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.866 ops/ms
# Warmup Iteration   2: 8.331 ops/ms
# Warmup Iteration   3: 9.361 ops/ms
Iteration   1: 9.391 ops/ms
Iteration   2: 9.406 ops/ms
Iteration   3: 9.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.463 ±(99.9%) 2.054 ops/ms [Average]
  (min, avg, max) = (9.391, 9.463, 9.593), stdev = 0.113
  CI (99.9%): [7.409, 11.517] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.942 ops/ms
# Warmup Iteration   2: 8.706 ops/ms
# Warmup Iteration   3: 8.818 ops/ms
Iteration   1: 8.686 ops/ms
Iteration   2: 9.178 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.982 ±(99.9%) 4.759 ops/ms [Average]
  (min, avg, max) = (8.686, 8.982, 9.178), stdev = 0.261
  CI (99.9%): [4.222, 13.741] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.733 ops/ms
# Warmup Iteration   2: 7.058 ops/ms
# Warmup Iteration   3: 7.631 ops/ms
Iteration   1: 7.672 ops/ms
Iteration   2: 7.648 ops/ms
Iteration   3: 7.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.625 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (7.556, 7.625, 7.672), stdev = 0.062
  CI (99.9%): [6.502, 8.749] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.673 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.004 ms/op
Iteration   1: 3.526 ±(99.9%) 0.004 ms/op
Iteration   2: 3.510 ±(99.9%) 0.004 ms/op
Iteration   3: 3.514 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.517 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (3.510, 3.517, 3.526), stdev = 0.008
  CI (99.9%): [3.365, 3.669] (assumes normal distribution)


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
# Warmup Iteration   1: 9.596 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.003 ms/op
Iteration   1: 3.397 ±(99.9%) 0.004 ms/op
Iteration   2: 3.336 ±(99.9%) 0.006 ms/op
Iteration   3: 3.322 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.322, 3.351, 3.397), stdev = 0.040
  CI (99.9%): [2.626, 4.077] (assumes normal distribution)


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
# Warmup Iteration   1: 9.728 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.570 ±(99.9%) 0.003 ms/op
Iteration   1: 3.408 ±(99.9%) 0.004 ms/op
Iteration   2: 3.520 ±(99.9%) 0.005 ms/op
Iteration   3: 3.420 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.450 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (3.408, 3.450, 3.520), stdev = 0.062
  CI (99.9%): [2.324, 4.575] (assumes normal distribution)


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
# Warmup Iteration   1: 10.595 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.005 ms/op
Iteration   1: 4.132 ±(99.9%) 0.006 ms/op
Iteration   2: 4.055 ±(99.9%) 0.008 ms/op
Iteration   3: 4.139 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.109 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (4.055, 4.109, 4.139), stdev = 0.047
  CI (99.9%): [3.255, 4.963] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.709 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.010 ms/op
Iteration   1: 3.467 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  20.478 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.519 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  21.924 ms/op
                 createUser·p0.9999: 25.713 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.575 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  21.004 ms/op
                 createUser·p0.9999: 26.491 ms/op
                 createUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272778
  mean =      3.520 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4256 
    [ 2.500,  5.000) = 262628 
    [ 5.000,  7.500) = 5050 
    [ 7.500, 10.000) = 341 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.043 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
Iteration   1: 3.453 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  12.303 ms/op
                 existUser·p0.9999: 20.332 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.389 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  19.340 ms/op
                 existUser·p0.9999: 22.268 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  18.434 ms/op
                 existUser·p0.9999: 22.792 ms/op
                 existUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281444
  mean =      3.409 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9189 
    [ 2.500,  5.000) = 265308 
    [ 5.000,  7.500) = 5539 
    [ 7.500, 10.000) = 872 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.161 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.441 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 7.977 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.010 ms/op
Iteration   1: 3.455 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 22.109 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.448 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  11.878 ms/op
                 getUser·p0.9999: 23.485 ms/op
                 getUser·p1.00:   24.969 ms/op

Iteration   3: 3.468 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  18.468 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277824
  mean =      3.457 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4267 
    [ 2.500,  5.000) = 267429 
    [ 5.000,  7.500) = 4952 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      6.371 ms/op
     p(99.9000) =     18.389 ms/op
     p(99.9900) =     24.485 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.141 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.578 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.013 ms/op
Iteration   1: 4.121 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  20.613 ms/op
                 listUser·p0.9999: 25.436 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   2: 4.179 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 16.821 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 4.280 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.081 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 16.865 ms/op
                 listUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229028
  mean =      4.192 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 216719 
    [ 5.000,  7.500) = 10265 
    [ 7.500, 10.000) = 1128 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     15.679 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     25.830 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.013 ± 2.015  ops/ms
ClientPb.existUser                       thrpt       3   9.463 ± 2.054  ops/ms
ClientPb.getUser                         thrpt       3   8.982 ± 4.759  ops/ms
ClientPb.listUser                        thrpt       3   7.625 ± 1.124  ops/ms
ClientPb.createUser                       avgt       3   3.517 ± 0.152   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 0.725   ms/op
ClientPb.getUser                          avgt       3   3.450 ± 1.126   ms/op
ClientPb.listUser                         avgt       3   4.109 ± 0.854   ms/op
ClientPb.createUser                     sample  272778   3.520 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.771           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.854           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.558           ms/op
ClientPb.existUser                      sample  281444   3.409 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.927           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.161           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.386           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.315           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.593           ms/op
ClientPb.getUser                        sample  277824   3.457 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.371           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.485           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.018           ms/op
ClientPb.listUser                       sample  229028   4.192 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.014           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.679           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.936           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.870           ms/op
