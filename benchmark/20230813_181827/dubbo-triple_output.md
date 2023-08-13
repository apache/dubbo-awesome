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
# Warmup Iteration   1: 2.202 ops/ms
# Warmup Iteration   2: 5.222 ops/ms
# Warmup Iteration   3: 8.480 ops/ms
Iteration   1: 8.982 ops/ms
Iteration   2: 9.266 ops/ms
Iteration   3: 9.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.104 ±(99.9%) 2.672 ops/ms [Average]
  (min, avg, max) = (8.982, 9.104, 9.266), stdev = 0.146
  CI (99.9%): [6.432, 11.776] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.886 ops/ms
# Warmup Iteration   2: 8.511 ops/ms
# Warmup Iteration   3: 9.040 ops/ms
Iteration   1: 9.026 ops/ms
Iteration   2: 9.060 ops/ms
Iteration   3: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.827 ±(99.9%) 6.832 ops/ms [Average]
  (min, avg, max) = (8.395, 8.827, 9.060), stdev = 0.374
  CI (99.9%): [1.996, 15.659] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.413 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 7.946 ops/ms
Iteration   2: 8.748 ops/ms
Iteration   3: 8.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.279 ±(99.9%) 7.628 ops/ms [Average]
  (min, avg, max) = (7.946, 8.279, 8.748), stdev = 0.418
  CI (99.9%): [0.651, 15.908] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.832 ops/ms
# Warmup Iteration   2: 6.091 ops/ms
# Warmup Iteration   3: 6.971 ops/ms
Iteration   1: 6.870 ops/ms
Iteration   2: 6.844 ops/ms
Iteration   3: 7.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.001 ±(99.9%) 4.538 ops/ms [Average]
  (min, avg, max) = (6.844, 7.001, 7.288), stdev = 0.249
  CI (99.9%): [2.463, 11.539] (assumes normal distribution)


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
# Warmup Iteration   1: 12.197 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.162 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.004 ms/op
Iteration   1: 3.891 ±(99.9%) 0.006 ms/op
Iteration   2: 3.750 ±(99.9%) 0.010 ms/op
Iteration   3: 3.705 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.782 ±(99.9%) 1.769 ms/op [Average]
  (min, avg, max) = (3.705, 3.782, 3.891), stdev = 0.097
  CI (99.9%): [2.013, 5.551] (assumes normal distribution)


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
# Warmup Iteration   1: 9.877 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.004 ms/op
Iteration   1: 3.544 ±(99.9%) 0.009 ms/op
Iteration   2: 3.590 ±(99.9%) 0.004 ms/op
Iteration   3: 3.568 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.567 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.544, 3.567, 3.590), stdev = 0.023
  CI (99.9%): [3.152, 3.983] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.471 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.004 ms/op
Iteration   1: 3.374 ±(99.9%) 0.006 ms/op
Iteration   2: 3.404 ±(99.9%) 0.007 ms/op
Iteration   3: 3.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.389 ±(99.9%) 0.274 ms/op [Average]
  (min, avg, max) = (3.374, 3.389, 3.404), stdev = 0.015
  CI (99.9%): [3.116, 3.663] (assumes normal distribution)


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
# Warmup Iteration   1: 10.783 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.008 ms/op
Iteration   1: 4.097 ±(99.9%) 0.008 ms/op
Iteration   2: 3.938 ±(99.9%) 0.011 ms/op
Iteration   3: 3.990 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.008 ±(99.9%) 1.476 ms/op [Average]
  (min, avg, max) = (3.938, 4.008, 4.097), stdev = 0.081
  CI (99.9%): [2.532, 5.484] (assumes normal distribution)


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
# Warmup Iteration   1: 9.409 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
Iteration   1: 3.552 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.262 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  20.182 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 3.508 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  20.919 ms/op
                 createUser·p0.9999: 24.568 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.527 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  16.691 ms/op
                 createUser·p0.9999: 24.506 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271889
  mean =      3.529 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4728 
    [ 2.500,  5.000) = 257081 
    [ 5.000,  7.500) = 8371 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     17.724 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 9.151 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.310 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  15.337 ms/op
                 existUser·p0.9999: 24.882 ms/op
                 existUser·p1.00:   25.756 ms/op

Iteration   2: 3.456 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.403 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 25.437 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  12.525 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286172
  mean =      3.352 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6166 
    [ 2.500,  5.000) = 272851 
    [ 5.000,  7.500) = 5663 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 176 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     18.376 ms/op
     p(99.9900) =     25.113 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 9.893 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.013 ms/op
Iteration   1: 3.690 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  13.900 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   2: 3.641 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.360 ms/op
                 getUser·p0.999:  24.971 ms/op
                 getUser·p0.9999: 35.025 ms/op
                 getUser·p1.00:   35.848 ms/op

Iteration   3: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.603 ms/op
                 getUser·p0.999:  23.874 ms/op
                 getUser·p0.9999: 32.436 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265022
  mean =      3.621 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1753 
    [ 2.500,  5.000) = 251193 
    [ 5.000,  7.500) = 9605 
    [ 7.500, 10.000) = 1662 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     13.992 ms/op
     p(99.9900) =     33.243 ms/op
     p(99.9990) =     35.763 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 11.984 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.018 ms/op
Iteration   1: 4.242 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  24.047 ms/op
                 listUser·p0.9999: 28.785 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   2: 4.254 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 18.923 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 4.244 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.950 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  16.499 ms/op
                 listUser·p0.9999: 19.837 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225967
  mean =      4.246 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 209191 
    [ 5.000,  7.500) = 13279 
    [ 7.500, 10.000) = 2534 
    [10.000, 12.500) = 414 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      8.176 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.104 ± 2.672  ops/ms
ClientPb.existUser                       thrpt       3   8.827 ± 6.832  ops/ms
ClientPb.getUser                         thrpt       3   8.279 ± 7.628  ops/ms
ClientPb.listUser                        thrpt       3   7.001 ± 4.538  ops/ms
ClientPb.createUser                       avgt       3   3.782 ± 1.769   ms/op
ClientPb.existUser                        avgt       3   3.567 ± 0.415   ms/op
ClientPb.getUser                          avgt       3   3.389 ± 0.274   ms/op
ClientPb.listUser                         avgt       3   4.008 ± 1.476   ms/op
ClientPb.createUser                     sample  271889   3.529 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.724           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.116           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  286172   3.352 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.100           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.199           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.332           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.376           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.113           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  265022   3.621 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.610           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.992           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.243           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  225967   4.246 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.159           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.433           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.049           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
