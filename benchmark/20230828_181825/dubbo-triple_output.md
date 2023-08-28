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
# Warmup Iteration   1: 1.925 ops/ms
# Warmup Iteration   2: 4.792 ops/ms
# Warmup Iteration   3: 8.233 ops/ms
Iteration   1: 8.723 ops/ms
Iteration   2: 9.362 ops/ms
Iteration   3: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.182 ±(99.9%) 7.296 ops/ms [Average]
  (min, avg, max) = (8.723, 9.182, 9.460), stdev = 0.400
  CI (99.9%): [1.886, 16.477] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.857 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 9.183 ops/ms
Iteration   1: 9.396 ops/ms
Iteration   2: 9.713 ops/ms
Iteration   3: 9.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.498 ±(99.9%) 3.410 ops/ms [Average]
  (min, avg, max) = (9.384, 9.498, 9.713), stdev = 0.187
  CI (99.9%): [6.088, 12.907] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 8.251 ops/ms
# Warmup Iteration   3: 8.742 ops/ms
Iteration   1: 8.978 ops/ms
Iteration   2: 9.215 ops/ms
Iteration   3: 8.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.047 ±(99.9%) 2.683 ops/ms [Average]
  (min, avg, max) = (8.947, 9.047, 9.215), stdev = 0.147
  CI (99.9%): [6.364, 11.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.813 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 7.573 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.625 ops/ms
Iteration   3: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.746 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (7.625, 7.746, 7.835), stdev = 0.108
  CI (99.9%): [5.767, 9.725] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.008 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.010 ms/op
Iteration   1: 3.750 ±(99.9%) 0.006 ms/op
Iteration   2: 3.612 ±(99.9%) 0.009 ms/op
Iteration   3: 3.454 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.605 ±(99.9%) 2.697 ms/op [Average]
  (min, avg, max) = (3.454, 3.605, 3.750), stdev = 0.148
  CI (99.9%): [0.908, 6.303] (assumes normal distribution)


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
# Warmup Iteration   1: 9.218 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.007 ms/op
Iteration   1: 3.361 ±(99.9%) 0.004 ms/op
Iteration   2: 3.278 ±(99.9%) 0.006 ms/op
Iteration   3: 3.377 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.339 ±(99.9%) 0.967 ms/op [Average]
  (min, avg, max) = (3.278, 3.339, 3.377), stdev = 0.053
  CI (99.9%): [2.371, 4.306] (assumes normal distribution)


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
# Warmup Iteration   1: 9.957 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.688 ±(99.9%) 0.005 ms/op
Iteration   1: 3.504 ±(99.9%) 0.008 ms/op
Iteration   2: 3.495 ±(99.9%) 0.003 ms/op
Iteration   3: 3.549 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.516 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (3.495, 3.516, 3.549), stdev = 0.029
  CI (99.9%): [2.988, 4.044] (assumes normal distribution)


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
# Warmup Iteration   1: 10.147 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.006 ms/op
Iteration   1: 4.206 ±(99.9%) 0.006 ms/op
Iteration   2: 4.060 ±(99.9%) 0.009 ms/op
Iteration   3: 4.009 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.092 ±(99.9%) 1.863 ms/op [Average]
  (min, avg, max) = (4.009, 4.092, 4.206), stdev = 0.102
  CI (99.9%): [2.229, 5.955] (assumes normal distribution)


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
# Warmup Iteration   1: 11.134 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.244 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.013 ms/op
Iteration   1: 3.571 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.741 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.680 ms/op
                 createUser·p0.999:  20.884 ms/op
                 createUser·p0.9999: 25.588 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 28.799 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 3.601 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.324 ms/op
                 createUser·p0.999:  19.923 ms/op
                 createUser·p0.9999: 34.284 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269627
  mean =      3.559 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6381 
    [ 2.500,  5.000) = 255061 
    [ 5.000,  7.500) = 6491 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     20.722 ms/op
     p(99.9900) =     33.426 ms/op
     p(99.9990) =     34.885 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 8.910 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.485 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 21.326 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   2: 3.515 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  20.646 ms/op
                 existUser·p0.9999: 31.442 ms/op
                 existUser·p1.00:   32.801 ms/op

Iteration   3: 3.358 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  11.268 ms/op
                 existUser·p0.9999: 28.669 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278095
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7273 
    [ 2.500,  5.000) = 260705 
    [ 5.000,  7.500) = 8313 
    [ 7.500, 10.000) = 1364 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.106 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     11.679 ms/op
     p(99.9900) =     30.022 ms/op
     p(99.9990) =     32.200 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 10.104 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.012 ms/op
Iteration   1: 3.687 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.855 ms/op
                 getUser·p0.999:  21.529 ms/op
                 getUser·p0.9999: 25.133 ms/op
                 getUser·p1.00:   25.723 ms/op

Iteration   2: 3.433 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.784 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.000 ms/op
                 getUser·p0.999:  11.615 ms/op
                 getUser·p0.9999: 24.753 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 30.361 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272027
  mean =      3.526 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11703 
    [ 2.500,  5.000) = 249781 
    [ 5.000,  7.500) = 8964 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     27.912 ms/op
     p(99.9990) =     30.795 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 11.243 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.013 ms/op
Iteration   1: 4.099 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   8.289 ms/op
                 listUser·p0.999:  21.561 ms/op
                 listUser·p0.9999: 23.520 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   2: 4.142 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.205 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 22.062 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  13.377 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235707
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 224717 
    [ 5.000,  7.500) = 7583 
    [ 7.500, 10.000) = 2216 
    [10.000, 12.500) = 650 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     15.827 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.508 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.182 ± 7.296  ops/ms
ClientPb.existUser                       thrpt       3   9.498 ± 3.410  ops/ms
ClientPb.getUser                         thrpt       3   9.047 ± 2.683  ops/ms
ClientPb.listUser                        thrpt       3   7.746 ± 1.979  ops/ms
ClientPb.createUser                       avgt       3   3.605 ± 2.697   ms/op
ClientPb.existUser                        avgt       3   3.339 ± 0.967   ms/op
ClientPb.getUser                          avgt       3   3.516 ± 0.528   ms/op
ClientPb.listUser                         avgt       3   4.092 ± 1.863   ms/op
ClientPb.createUser                     sample  269627   3.559 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.774           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.473           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.722           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.426           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  278095   3.451 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.106           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.955           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.679           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.022           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.801           ms/op
ClientPb.getUser                        sample  272027   3.526 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.173           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.912           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  235707   4.069 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.827           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.904           ms/op
