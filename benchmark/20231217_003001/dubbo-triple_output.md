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
# Warmup Iteration   1: 4.985 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.565 ops/ms
Iteration   1: 12.666 ops/ms
Iteration   2: 12.731 ops/ms
Iteration   3: 12.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.671 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (12.615, 12.671, 12.731), stdev = 0.058
  CI (99.9%): [11.612, 13.730] (assumes normal distribution)


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
# Warmup Iteration   1: 8.189 ops/ms
# Warmup Iteration   2: 13.239 ops/ms
# Warmup Iteration   3: 13.257 ops/ms
Iteration   1: 13.143 ops/ms
Iteration   2: 13.301 ops/ms
Iteration   3: 13.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.183 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (13.105, 13.183, 13.301), stdev = 0.104
  CI (99.9%): [11.288, 15.079] (assumes normal distribution)


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
# Warmup Iteration   1: 7.675 ops/ms
# Warmup Iteration   2: 12.713 ops/ms
# Warmup Iteration   3: 12.677 ops/ms
Iteration   1: 13.118 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.023 ±(99.9%) 1.604 ops/ms [Average]
  (min, avg, max) = (12.943, 13.023, 13.118), stdev = 0.088
  CI (99.9%): [11.420, 14.627] (assumes normal distribution)


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
# Warmup Iteration   1: 6.580 ops/ms
# Warmup Iteration   2: 10.541 ops/ms
# Warmup Iteration   3: 10.622 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.534 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.578 ±(99.9%) 0.704 ops/ms [Average]
  (min, avg, max) = (10.534, 10.578, 10.608), stdev = 0.039
  CI (99.9%): [9.874, 11.281] (assumes normal distribution)


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.490 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.469, 2.490, 2.517), stdev = 0.025
  CI (99.9%): [2.038, 2.942] (assumes normal distribution)


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.446 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (2.429, 2.446, 2.463), stdev = 0.017
  CI (99.9%): [2.136, 2.757] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.475 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.467, 2.475, 2.481), stdev = 0.007
  CI (99.9%): [2.347, 2.603] (assumes normal distribution)


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.005 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
Iteration   3: 2.979 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.979 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.969, 2.979, 2.989), stdev = 0.010
  CI (99.9%): [2.800, 3.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.633 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.613 ms/op
                 createUser·p0.999:  12.072 ms/op
                 createUser·p0.9999: 14.795 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  8.801 ms/op
                 createUser·p0.9999: 11.947 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  7.922 ms/op
                 createUser·p0.9999: 9.708 ms/op
                 createUser·p1.00:   9.978 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384409
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 185895 
    [ 2.500,  3.750) = 194014 
    [ 3.750,  5.000) = 3676 
    [ 5.000,  6.250) = 300 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.513 ms/op
     p(99.9900) =     13.460 ms/op
     p(99.9990) =     14.912 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 3.593 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  5.182 ms/op
                 existUser·p0.9999: 13.444 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.280 ms/op
                 existUser·p0.9999: 12.060 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.613 ms/op
                 existUser·p0.999:  8.422 ms/op
                 existUser·p0.9999: 11.538 ms/op
                 existUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396254
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 199285 
    [ 2.500,  3.750) = 194515 
    [ 3.750,  5.000) = 1812 
    [ 5.000,  6.250) = 126 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      8.315 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.681 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.006 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.633 ms/op
                 getUser·p0.999:  5.744 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.628 ms/op
                 getUser·p0.999:  6.223 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.539 ms/op
                 getUser·p0.9999: 10.933 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391619
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 197564 
    [ 2.500,  3.750) = 189528 
    [ 3.750,  5.000) = 3325 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      6.480 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     13.753 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.408 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 10.709 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.482 ms/op
                 listUser·p0.999:  9.578 ms/op
                 listUser·p0.9999: 11.720 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.071 ms/op
                 listUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318546
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 91218 
    [ 2.500,  3.750) = 189067 
    [ 3.750,  5.000) = 30911 
    [ 5.000,  6.250) = 5823 
    [ 6.250,  7.500) = 704 
    [ 7.500,  8.750) = 264 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.322 ms/op
     p(99.9900) =     11.139 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.671 ± 1.059  ops/ms
ClientPb.existUser                       thrpt       3  13.183 ± 1.896  ops/ms
ClientPb.getUser                         thrpt       3  13.023 ± 1.604  ops/ms
ClientPb.listUser                        thrpt       3  10.578 ± 0.704  ops/ms
ClientPb.createUser                       avgt       3   2.490 ± 0.452   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.310   ms/op
ClientPb.getUser                          avgt       3   2.475 ± 0.128   ms/op
ClientPb.listUser                         avgt       3   2.979 ± 0.179   ms/op
ClientPb.createUser                     sample  384409   2.495 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.983           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.513           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.975           ms/op
ClientPb.existUser                      sample  396254   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.691           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.315           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.960           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.926           ms/op
ClientPb.getUser                        sample  391619   2.449 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.887           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.978           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.042           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.910           ms/op
ClientPb.listUser                       sample  318546   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.408           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.322           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.139           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
