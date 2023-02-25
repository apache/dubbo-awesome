# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.886 ops/ms
# Warmup Iteration   2: 4.961 ops/ms
# Warmup Iteration   3: 8.327 ops/ms
Iteration   1: 9.211 ops/ms
Iteration   2: 9.051 ops/ms
Iteration   3: 9.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.252 ±(99.9%) 4.090 ops/ms [Average]
  (min, avg, max) = (9.051, 9.252, 9.494), stdev = 0.224
  CI (99.9%): [5.162, 13.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.478 ops/ms
# Warmup Iteration   2: 8.676 ops/ms
# Warmup Iteration   3: 9.273 ops/ms
Iteration   1: 9.580 ops/ms
Iteration   2: 9.838 ops/ms
Iteration   3: 9.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.785 ±(99.9%) 3.366 ops/ms [Average]
  (min, avg, max) = (9.580, 9.785, 9.938), stdev = 0.185
  CI (99.9%): [6.419, 13.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.013 ops/ms
# Warmup Iteration   2: 8.369 ops/ms
# Warmup Iteration   3: 8.975 ops/ms
Iteration   1: 9.441 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.407 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (9.377, 9.407, 9.441), stdev = 0.032
  CI (99.9%): [8.816, 9.998] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.953 ops/ms
# Warmup Iteration   2: 7.166 ops/ms
# Warmup Iteration   3: 7.530 ops/ms
Iteration   1: 7.825 ops/ms
Iteration   2: 7.764 ops/ms
Iteration   3: 7.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.722 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (7.576, 7.722, 7.825), stdev = 0.130
  CI (99.9%): [5.359, 10.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.630 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.007 ms/op
Iteration   1: 3.491 ±(99.9%) 0.004 ms/op
Iteration   2: 3.573 ±(99.9%) 0.007 ms/op
Iteration   3: 3.332 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.465 ±(99.9%) 2.240 ms/op [Average]
  (min, avg, max) = (3.332, 3.465, 3.573), stdev = 0.123
  CI (99.9%): [1.225, 5.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.578 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.005 ms/op
Iteration   1: 3.260 ±(99.9%) 0.012 ms/op
Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
Iteration   3: 3.287 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.260, 3.292, 3.330), stdev = 0.035
  CI (99.9%): [2.648, 3.937] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.471 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.006 ms/op
Iteration   1: 3.499 ±(99.9%) 0.004 ms/op
Iteration   2: 3.463 ±(99.9%) 0.008 ms/op
Iteration   3: 3.353 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.438 ±(99.9%) 1.391 ms/op [Average]
  (min, avg, max) = (3.353, 3.438, 3.499), stdev = 0.076
  CI (99.9%): [2.047, 4.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.811 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.695 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.011 ms/op
Iteration   1: 4.107 ±(99.9%) 0.010 ms/op
Iteration   2: 4.051 ±(99.9%) 0.010 ms/op
Iteration   3: 3.992 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.050 ±(99.9%) 1.053 ms/op [Average]
  (min, avg, max) = (3.992, 4.050, 4.107), stdev = 0.058
  CI (99.9%): [2.997, 5.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.005 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.012 ms/op
Iteration   1: 3.707 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  20.786 ms/op
                 createUser·p0.9999: 24.845 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.461 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.151 ms/op
                 createUser·p0.999:  24.718 ms/op
                 createUser·p0.9999: 29.745 ms/op
                 createUser·p1.00:   30.769 ms/op

Iteration   3: 3.452 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 25.714 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271457
  mean =      3.536 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3464 
    [ 2.500,  5.000) = 256781 
    [ 5.000,  7.500) = 9321 
    [ 7.500, 10.000) = 1292 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     19.318 ms/op
     p(99.9900) =     28.208 ms/op
     p(99.9990) =     30.306 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.442 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.735 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.663 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  20.139 ms/op
                 existUser·p0.9999: 23.341 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.416 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  23.506 ms/op
                 existUser·p0.9999: 26.792 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.359 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  13.500 ms/op
                 existUser·p0.9999: 30.081 ms/op
                 existUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282261
  mean =      3.399 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3420 
    [ 2.500,  5.000) = 270118 
    [ 5.000,  7.500) = 7642 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     30.929 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.150 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 3.796 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.012 ms/op
Iteration   1: 3.608 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.939 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.610 ms/op
                 getUser·p0.999:  22.655 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   2: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.360 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  23.257 ms/op
                 getUser·p0.9999: 26.402 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.474 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.862 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  22.246 ms/op
                 getUser·p0.9999: 28.839 ms/op
                 getUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273354
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11351 
    [ 2.500,  5.000) = 251688 
    [ 5.000,  7.500) = 8576 
    [ 7.500, 10.000) = 1190 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 171 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     22.369 ms/op
     p(99.9900) =     26.990 ms/op
     p(99.9990) =     29.172 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.651 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.014 ms/op
Iteration   1: 4.073 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.784 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  21.298 ms/op
                 listUser·p0.9999: 28.490 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   2: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  16.690 ms/op
                 listUser·p0.9999: 22.944 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 4.124 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235123
  mean =      4.081 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 225332 
    [ 5.000,  7.500) = 7106 
    [ 7.500, 10.000) = 1774 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     27.786 ms/op
     p(99.9990) =     29.971 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.252 ± 4.090  ops/ms
ClientPb.existUser                       thrpt       3   9.785 ± 3.366  ops/ms
ClientPb.getUser                         thrpt       3   9.407 ± 0.591  ops/ms
ClientPb.listUser                        thrpt       3   7.722 ± 2.363  ops/ms
ClientPb.createUser                       avgt       3   3.465 ± 2.240   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 0.644   ms/op
ClientPb.getUser                          avgt       3   3.438 ± 1.391   ms/op
ClientPb.listUser                         avgt       3   4.050 ± 1.053   ms/op
ClientPb.createUser                     sample  271457   3.536 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.922           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.318           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.208           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.769           ms/op
ClientPb.existUser                      sample  282261   3.399 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.324           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.550           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.443           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.064           ms/op
ClientPb.getUser                        sample  273354   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.360           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.369           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.990           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  235123   4.081 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.784           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.850           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.815           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.891           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.786           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.015           ms/op
