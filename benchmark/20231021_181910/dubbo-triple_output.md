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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.901 ops/ms
# Warmup Iteration   3: 8.625 ops/ms
Iteration   1: 9.139 ops/ms
Iteration   2: 9.390 ops/ms
Iteration   3: 9.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.252 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (9.139, 9.252, 9.390), stdev = 0.127
  CI (99.9%): [6.928, 11.576] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.273 ops/ms
# Warmup Iteration   2: 8.874 ops/ms
# Warmup Iteration   3: 9.470 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 9.492 ops/ms
Iteration   3: 9.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.620 ±(99.9%) 2.774 ops/ms [Average]
  (min, avg, max) = (9.492, 9.620, 9.788), stdev = 0.152
  CI (99.9%): [6.846, 12.394] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ops/ms
# Warmup Iteration   2: 8.140 ops/ms
# Warmup Iteration   3: 8.887 ops/ms
Iteration   1: 9.154 ops/ms
Iteration   2: 9.074 ops/ms
Iteration   3: 9.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.181 ±(99.9%) 2.242 ops/ms [Average]
  (min, avg, max) = (9.074, 9.181, 9.315), stdev = 0.123
  CI (99.9%): [6.939, 11.423] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.660 ops/ms
# Warmup Iteration   2: 7.265 ops/ms
# Warmup Iteration   3: 7.702 ops/ms
Iteration   1: 7.667 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 7.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.746 ±(99.9%) 2.395 ops/ms [Average]
  (min, avg, max) = (7.667, 7.746, 7.898), stdev = 0.131
  CI (99.9%): [5.352, 10.141] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.982 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.006 ms/op
Iteration   1: 3.537 ±(99.9%) 0.006 ms/op
Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
Iteration   3: 3.356 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.423 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.356, 3.423, 3.537), stdev = 0.099
  CI (99.9%): [1.608, 5.237] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.759 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.002 ms/op
Iteration   1: 3.292 ±(99.9%) 0.004 ms/op
Iteration   2: 3.346 ±(99.9%) 0.002 ms/op
Iteration   3: 3.331 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.323 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.292, 3.323, 3.346), stdev = 0.028
  CI (99.9%): [2.809, 3.837] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.447 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.003 ms/op
Iteration   1: 3.459 ±(99.9%) 0.003 ms/op
Iteration   2: 3.571 ±(99.9%) 0.005 ms/op
Iteration   3: 3.556 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.529 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.459, 3.529, 3.571), stdev = 0.061
  CI (99.9%): [2.423, 4.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.279 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.005 ms/op
Iteration   1: 4.234 ±(99.9%) 0.005 ms/op
Iteration   2: 4.310 ±(99.9%) 0.009 ms/op
Iteration   3: 4.295 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.280 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (4.234, 4.280, 4.310), stdev = 0.040
  CI (99.9%): [3.550, 5.010] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.744 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.018 ms/op
Iteration   1: 3.668 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.506 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  23.128 ms/op
                 createUser·p0.9999: 25.306 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 3.613 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  10.255 ms/op
                 createUser·p0.9999: 29.889 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   3: 3.582 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  27.673 ms/op
                 createUser·p0.9999: 33.690 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264952
  mean =      3.621 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2292 
    [ 2.500,  5.000) = 256930 
    [ 5.000,  7.500) = 4500 
    [ 7.500, 10.000) = 598 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     31.965 ms/op
     p(99.9990) =     34.102 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 10.773 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
Iteration   1: 3.526 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.074 ms/op
                 existUser·p0.999:  21.479 ms/op
                 existUser·p0.9999: 25.589 ms/op
                 existUser·p1.00:   25.919 ms/op

Iteration   2: 3.415 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   5.880 ms/op
                 existUser·p0.999:  21.505 ms/op
                 existUser·p0.9999: 27.742 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.781 ms/op
                 existUser·p0.999:  15.058 ms/op
                 existUser·p0.9999: 28.070 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278209
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8146 
    [ 2.500,  5.000) = 265306 
    [ 5.000,  7.500) = 3503 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     15.807 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     28.555 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.805 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.719 ±(99.9%) 0.013 ms/op
Iteration   1: 3.521 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.292 ms/op
                 getUser·p0.999:  21.004 ms/op
                 getUser·p0.9999: 23.917 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   2: 3.427 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  23.050 ms/op
                 getUser·p0.9999: 25.483 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.543 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  17.850 ms/op
                 getUser·p0.9999: 28.475 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274344
  mean =      3.496 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4303 
    [ 2.500,  5.000) = 263659 
    [ 5.000,  7.500) = 5021 
    [ 7.500, 10.000) = 824 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     27.628 ms/op
     p(99.9990) =     28.853 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 10.815 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.014 ms/op
Iteration   1: 4.078 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  20.431 ms/op
                 listUser·p0.9999: 24.099 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.148 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.961 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 17.213 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 4.064 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  15.486 ms/op
                 listUser·p0.9999: 17.404 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234456
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 225317 
    [ 5.000,  7.500) = 6900 
    [ 7.500, 10.000) = 1309 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.311 ms/op
     p(99.9900) =     23.578 ms/op
     p(99.9990) =     24.487 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.252 ± 2.324  ops/ms
ClientPb.existUser                       thrpt       3   9.620 ± 2.774  ops/ms
ClientPb.getUser                         thrpt       3   9.181 ± 2.242  ops/ms
ClientPb.listUser                        thrpt       3   7.746 ± 2.395  ops/ms
ClientPb.createUser                       avgt       3   3.423 ± 1.815   ms/op
ClientPb.existUser                        avgt       3   3.323 ± 0.514   ms/op
ClientPb.getUser                          avgt       3   3.529 ± 1.106   ms/op
ClientPb.listUser                         avgt       3   4.280 ± 0.730   ms/op
ClientPb.createUser                     sample  264952   3.621 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.055           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.510           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.116           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.095           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.337           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.965           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  278209   3.451 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.425           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.807           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705           ms/op
ClientPb.getUser                        sample  274344   3.496 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.178           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.137           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.678           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.628           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.131           ms/op
ClientPb.listUser                       sample  234456   4.096 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.655           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.784           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.311           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.578           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
