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
# Warmup Iteration   1: 5.152 ops/ms
# Warmup Iteration   2: 12.381 ops/ms
# Warmup Iteration   3: 12.272 ops/ms
Iteration   1: 12.513 ops/ms
Iteration   2: 12.589 ops/ms
Iteration   3: 12.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.550 ±(99.9%) 0.690 ops/ms [Average]
  (min, avg, max) = (12.513, 12.550, 12.589), stdev = 0.038
  CI (99.9%): [11.860, 13.240] (assumes normal distribution)


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
# Warmup Iteration   1: 8.623 ops/ms
# Warmup Iteration   2: 12.991 ops/ms
# Warmup Iteration   3: 13.089 ops/ms
Iteration   1: 13.016 ops/ms
Iteration   2: 13.061 ops/ms
Iteration   3: 12.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.018 ±(99.9%) 0.771 ops/ms [Average]
  (min, avg, max) = (12.976, 13.018, 13.061), stdev = 0.042
  CI (99.9%): [12.247, 13.789] (assumes normal distribution)


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
# Warmup Iteration   1: 8.165 ops/ms
# Warmup Iteration   2: 12.548 ops/ms
# Warmup Iteration   3: 12.660 ops/ms
Iteration   1: 12.647 ops/ms
Iteration   2: 12.710 ops/ms
Iteration   3: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.699 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (12.647, 12.699, 12.742), stdev = 0.048
  CI (99.9%): [11.819, 13.580] (assumes normal distribution)


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
# Warmup Iteration   1: 6.929 ops/ms
# Warmup Iteration   2: 10.222 ops/ms
# Warmup Iteration   3: 10.473 ops/ms
Iteration   1: 10.685 ops/ms
Iteration   2: 10.488 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.562 ±(99.9%) 1.969 ops/ms [Average]
  (min, avg, max) = (10.488, 10.562, 10.685), stdev = 0.108
  CI (99.9%): [8.592, 12.531] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.005 ms/op
Iteration   1: 2.553 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.580 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.541, 2.558, 2.580), stdev = 0.020
  CI (99.9%): [2.202, 2.914] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (2.442, 2.465, 2.488), stdev = 0.023
  CI (99.9%): [2.051, 2.879] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.863 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.512 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.496, 2.512, 2.528), stdev = 0.016
  CI (99.9%): [2.218, 2.805] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.653 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.021 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.008, 3.021, 3.045), stdev = 0.021
  CI (99.9%): [2.647, 3.395] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  11.180 ms/op
                 createUser·p0.9999: 13.974 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 12.229 ms/op
                 createUser·p1.00:   12.861 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.412 ms/op
                 createUser·p0.9999: 11.067 ms/op
                 createUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377177
  mean =      2.543 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 180784 
    [ 2.500,  3.750) = 191631 
    [ 3.750,  5.000) = 3777 
    [ 5.000,  6.250) = 480 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.468 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.489 ms/op
                 existUser·p0.9999: 14.025 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  7.364 ms/op
                 existUser·p0.9999: 14.907 ms/op
                 existUser·p1.00:   16.646 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  5.756 ms/op
                 existUser·p0.9999: 12.291 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385536
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 187954 
    [ 2.500,  3.750) = 193932 
    [ 3.750,  5.000) = 2950 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      6.295 ms/op
     p(99.9900) =     13.988 ms/op
     p(99.9990) =     15.695 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.600 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   3.903 ms/op
                 getUser·p0.999:  11.022 ms/op
                 getUser·p0.9999: 13.670 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.785 ms/op
                 getUser·p0.999:  8.684 ms/op
                 getUser·p0.9999: 13.448 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  9.164 ms/op
                 getUser·p0.9999: 11.139 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377892
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 182875 
    [ 2.500,  3.750) = 190083 
    [ 3.750,  5.000) = 3892 
    [ 5.000,  6.250) = 587 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.367 ms/op
     p(99.9990) =     14.258 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  8.927 ms/op
                 listUser·p0.9999: 11.789 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   2: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.797 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.059 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.053 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.321 ms/op
                 listUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315427
  mean =      3.041 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 87145 
    [ 2.500,  3.750) = 187313 
    [ 3.750,  5.000) = 32961 
    [ 5.000,  6.250) = 6534 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     11.360 ms/op
     p(99.9990) =     12.719 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.550 ± 0.690  ops/ms
ClientPb.existUser                       thrpt       3  13.018 ± 0.771  ops/ms
ClientPb.getUser                         thrpt       3  12.699 ± 0.880  ops/ms
ClientPb.listUser                        thrpt       3  10.562 ± 1.969  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.356   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.414   ms/op
ClientPb.getUser                          avgt       3   2.512 ± 0.294   ms/op
ClientPb.listUser                         avgt       3   3.021 ± 0.374   ms/op
ClientPb.createUser                     sample  377177   2.543 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.708           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.468           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.647           ms/op
ClientPb.existUser                      sample  385536   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.819           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.295           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.988           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.646           ms/op
ClientPb.getUser                        sample  377892   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.882           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.765           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.367           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.369           ms/op
ClientPb.listUser                       sample  315427   3.041 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.797           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.360           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
