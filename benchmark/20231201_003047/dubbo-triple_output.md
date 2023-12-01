# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.813 ops/ms
# Warmup Iteration   2: 11.938 ops/ms
# Warmup Iteration   3: 12.242 ops/ms
Iteration   1: 12.380 ops/ms
Iteration   2: 12.420 ops/ms
Iteration   3: 12.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.417 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (12.380, 12.417, 12.451), stdev = 0.036
  CI (99.9%): [11.765, 13.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ops/ms
# Warmup Iteration   2: 12.833 ops/ms
# Warmup Iteration   3: 13.206 ops/ms
Iteration   1: 13.190 ops/ms
Iteration   2: 13.090 ops/ms
Iteration   3: 12.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.077 ±(99.9%) 2.187 ops/ms [Average]
  (min, avg, max) = (12.951, 13.077, 13.190), stdev = 0.120
  CI (99.9%): [10.890, 15.264] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.510 ops/ms
# Warmup Iteration   2: 12.554 ops/ms
# Warmup Iteration   3: 12.806 ops/ms
Iteration   1: 12.853 ops/ms
Iteration   2: 12.767 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.822 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (12.767, 12.822, 12.853), stdev = 0.048
  CI (99.9%): [11.942, 13.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.050 ops/ms
# Warmup Iteration   2: 10.575 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.710 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.651 ±(99.9%) 0.939 ops/ms [Average]
  (min, avg, max) = (10.616, 10.651, 10.710), stdev = 0.051
  CI (99.9%): [9.712, 11.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.932 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.003 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.003 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.494 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.482, 2.494, 2.509), stdev = 0.014
  CI (99.9%): [2.244, 2.744] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.472 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.460 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (2.448, 2.460, 2.472), stdev = 0.012
  CI (99.9%): [2.246, 2.674] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.003 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.525 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.190 ms/op [Average]
  (min, avg, max) = (2.505, 2.514, 2.525), stdev = 0.010
  CI (99.9%): [2.324, 2.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.663 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.005 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.983 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (2.980, 2.983, 2.986), stdev = 0.003
  CI (99.9%): [2.925, 3.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 13.652 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.832 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 16.105 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.685 ms/op
                 createUser·p0.9999: 13.521 ms/op
                 createUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381455
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184987 
    [ 2.500,  3.750) = 192052 
    [ 3.750,  5.000) = 3562 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.823 ms/op
     p(99.9000) =      8.914 ms/op
     p(99.9900) =     14.135 ms/op
     p(99.9990) =     16.564 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 14.633 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  6.475 ms/op
                 existUser·p0.9999: 14.065 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  8.420 ms/op
                 existUser·p0.9999: 11.819 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386256
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 190232 
    [ 2.500,  3.750) = 192512 
    [ 3.750,  5.000) = 2722 
    [ 5.000,  6.250) = 391 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.062 ms/op
     p(99.9900) =     13.998 ms/op
     p(99.9990) =     14.881 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.832 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.891 ms/op
                 getUser·p0.999:  5.825 ms/op
                 getUser·p0.9999: 14.123 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  9.189 ms/op
                 getUser·p0.9999: 14.286 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 11.551 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382583
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 188589 
    [ 2.500,  3.750) = 189325 
    [ 3.750,  5.000) = 3707 
    [ 5.000,  6.250) = 499 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     14.053 ms/op
     p(99.9990) =     14.528 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.698 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.009 ms/op
Iteration   1: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.411 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.202 ms/op
                 listUser·p0.9999: 10.541 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.342 ms/op
                 listUser·p0.9999: 11.161 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.304 ms/op
                 listUser·p0.9999: 11.057 ms/op
                 listUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319871
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 95511 
    [ 2.500,  3.750) = 186541 
    [ 3.750,  5.000) = 30855 
    [ 5.000,  6.250) = 5562 
    [ 6.250,  7.500) = 601 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     11.629 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.417 ± 0.653  ops/ms
ClientPb.existUser                       thrpt       3  13.077 ± 2.187  ops/ms
ClientPb.getUser                         thrpt       3  12.822 ± 0.880  ops/ms
ClientPb.listUser                        thrpt       3  10.651 ± 0.939  ops/ms
ClientPb.createUser                       avgt       3   2.494 ± 0.250   ms/op
ClientPb.existUser                        avgt       3   2.460 ± 0.214   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.190   ms/op
ClientPb.listUser                         avgt       3   2.983 ± 0.057   ms/op
ClientPb.createUser                     sample  381455   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.879           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.823           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.914           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.135           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.695           ms/op
ClientPb.existUser                      sample  386256   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.062           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.998           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.041           ms/op
ClientPb.getUser                        sample  382583   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.733           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.250           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.746           ms/op
ClientPb.listUser                       sample  319871   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.835           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.273           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.912           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.386           ms/op
