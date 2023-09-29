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
# Warmup Iteration   1: 2.043 ops/ms
# Warmup Iteration   2: 5.017 ops/ms
# Warmup Iteration   3: 8.531 ops/ms
Iteration   1: 8.986 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 9.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.997 ±(99.9%) 2.524 ops/ms [Average]
  (min, avg, max) = (8.864, 8.997, 9.140), stdev = 0.138
  CI (99.9%): [6.473, 11.520] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 9.018 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.729 ops/ms
Iteration   2: 9.482 ops/ms
Iteration   3: 9.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.664 ±(99.9%) 2.917 ops/ms [Average]
  (min, avg, max) = (9.482, 9.664, 9.782), stdev = 0.160
  CI (99.9%): [6.747, 12.581] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.196 ops/ms
# Warmup Iteration   3: 9.105 ops/ms
Iteration   1: 9.199 ops/ms
Iteration   2: 9.118 ops/ms
Iteration   3: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.137 ±(99.9%) 0.991 ops/ms [Average]
  (min, avg, max) = (9.096, 9.137, 9.199), stdev = 0.054
  CI (99.9%): [8.146, 10.129] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.491 ops/ms
# Warmup Iteration   2: 7.099 ops/ms
# Warmup Iteration   3: 7.616 ops/ms
Iteration   1: 7.661 ops/ms
Iteration   2: 7.779 ops/ms
Iteration   3: 7.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.763 ±(99.9%) 1.734 ops/ms [Average]
  (min, avg, max) = (7.661, 7.763, 7.849), stdev = 0.095
  CI (99.9%): [6.029, 9.497] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 9.830 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.003 ms/op
Iteration   1: 3.470 ±(99.9%) 0.004 ms/op
Iteration   2: 3.541 ±(99.9%) 0.003 ms/op
Iteration   3: 3.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.495 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.470, 3.495, 3.541), stdev = 0.040
  CI (99.9%): [2.773, 4.217] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.415 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.003 ms/op
Iteration   1: 3.318 ±(99.9%) 0.002 ms/op
Iteration   2: 3.386 ±(99.9%) 0.001 ms/op
Iteration   3: 3.348 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.351 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.318, 3.351, 3.386), stdev = 0.034
  CI (99.9%): [2.729, 3.973] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.283 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.633 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.003 ms/op
Iteration   1: 3.427 ±(99.9%) 0.003 ms/op
Iteration   2: 3.435 ±(99.9%) 0.004 ms/op
Iteration   3: 3.394 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.419 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.394, 3.419, 3.435), stdev = 0.022
  CI (99.9%): [3.023, 3.815] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.451 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.006 ms/op
Iteration   1: 4.081 ±(99.9%) 0.008 ms/op
Iteration   2: 4.134 ±(99.9%) 0.006 ms/op
Iteration   3: 4.044 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.086 ±(99.9%) 0.827 ms/op [Average]
  (min, avg, max) = (4.044, 4.086, 4.134), stdev = 0.045
  CI (99.9%): [3.260, 4.913] (assumes normal distribution)


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
# Warmup Iteration   1: 10.091 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.010 ms/op
Iteration   1: 3.724 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  11.387 ms/op
                 createUser·p0.9999: 26.752 ms/op
                 createUser·p1.00:   29.721 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  24.490 ms/op
                 createUser·p0.9999: 26.083 ms/op
                 createUser·p1.00:   26.378 ms/op

Iteration   3: 3.512 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  12.812 ms/op
                 createUser·p0.9999: 28.636 ms/op
                 createUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270477
  mean =      3.547 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5046 
    [ 2.500,  5.000) = 256395 
    [ 5.000,  7.500) = 7503 
    [ 7.500, 10.000) = 979 
    [10.000, 12.500) = 256 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.908 ms/op
     p(99.9900) =     27.584 ms/op
     p(99.9990) =     29.605 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 8.700 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.008 ms/op
Iteration   1: 3.347 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  11.548 ms/op
                 existUser·p0.9999: 22.606 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.438 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  23.025 ms/op
                 existUser·p0.9999: 26.182 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.351 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  20.813 ms/op
                 existUser·p0.9999: 28.017 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283347
  mean =      3.386 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5677 
    [ 2.500,  5.000) = 270763 
    [ 5.000,  7.500) = 5819 
    [ 7.500, 10.000) = 567 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     21.113 ms/op
     p(99.9900) =     26.782 ms/op
     p(99.9990) =     28.284 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 10.665 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.009 ms/op
Iteration   1: 3.556 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  20.185 ms/op
                 getUser·p0.9999: 23.397 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   2: 3.484 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.371 ms/op
                 getUser·p0.999:  23.074 ms/op
                 getUser·p0.9999: 25.508 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.518 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  18.805 ms/op
                 getUser·p0.9999: 26.637 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272760
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4779 
    [ 2.500,  5.000) = 258525 
    [ 5.000,  7.500) = 7633 
    [ 7.500, 10.000) = 1085 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     26.032 ms/op
     p(99.9990) =     27.060 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 13.105 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.013 ms/op
Iteration   1: 4.151 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.746 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  21.229 ms/op
                 listUser·p0.9999: 24.716 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   2: 4.146 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.314 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.984 ms/op
                 listUser·p0.9999: 16.061 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 4.142 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  15.331 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231559
  mean =      4.146 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 222945 
    [ 5.000,  7.500) = 6562 
    [ 7.500, 10.000) = 1156 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.719 ms/op
     p(99.9900) =     23.195 ms/op
     p(99.9990) =     25.026 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.997 ± 2.524  ops/ms
ClientPb.existUser                       thrpt       3   9.664 ± 2.917  ops/ms
ClientPb.getUser                         thrpt       3   9.137 ± 0.991  ops/ms
ClientPb.listUser                        thrpt       3   7.763 ± 1.734  ops/ms
ClientPb.createUser                       avgt       3   3.495 ± 0.722   ms/op
ClientPb.existUser                        avgt       3   3.351 ± 0.622   ms/op
ClientPb.getUser                          avgt       3   3.419 ± 0.396   ms/op
ClientPb.listUser                         avgt       3   4.086 ± 0.827   ms/op
ClientPb.createUser                     sample  270477   3.547 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.070           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.584           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.786           ms/op
ClientPb.existUser                      sample  283347   3.386 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.351           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.242           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.113           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.782           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  272760   3.519 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.759           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.032           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.296           ms/op
ClientPb.listUser                       sample  231559   4.146 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.288           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.719           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.195           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.494           ms/op
