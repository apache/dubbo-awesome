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
# Warmup Iteration   1: 4.664 ops/ms
# Warmup Iteration   2: 11.874 ops/ms
# Warmup Iteration   3: 12.281 ops/ms
Iteration   1: 12.559 ops/ms
Iteration   2: 12.694 ops/ms
Iteration   3: 12.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.628 ±(99.9%) 1.231 ops/ms [Average]
  (min, avg, max) = (12.559, 12.628, 12.694), stdev = 0.067
  CI (99.9%): [11.396, 13.859] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.967 ops/ms
# Warmup Iteration   2: 13.085 ops/ms
# Warmup Iteration   3: 12.918 ops/ms
Iteration   1: 13.131 ops/ms
Iteration   2: 13.140 ops/ms
Iteration   3: 13.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.140 ±(99.9%) 0.173 ops/ms [Average]
  (min, avg, max) = (13.131, 13.140, 13.150), stdev = 0.009
  CI (99.9%): [12.967, 13.313] (assumes normal distribution)


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
# Warmup Iteration   1: 7.966 ops/ms
# Warmup Iteration   2: 12.579 ops/ms
# Warmup Iteration   3: 12.834 ops/ms
Iteration   1: 13.030 ops/ms
Iteration   2: 12.996 ops/ms
Iteration   3: 12.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.963 ±(99.9%) 1.589 ops/ms [Average]
  (min, avg, max) = (12.865, 12.963, 13.030), stdev = 0.087
  CI (99.9%): [11.375, 14.552] (assumes normal distribution)


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
# Warmup Iteration   1: 6.861 ops/ms
# Warmup Iteration   2: 10.675 ops/ms
# Warmup Iteration   3: 10.714 ops/ms
Iteration   1: 10.837 ops/ms
Iteration   2: 10.896 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.855 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (10.834, 10.855, 10.896), stdev = 0.035
  CI (99.9%): [10.219, 11.492] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.482 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.481, 2.495, 2.520), stdev = 0.022
  CI (99.9%): [2.086, 2.903] (assumes normal distribution)


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.004 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
Iteration   3: 2.444 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.424, 2.441, 2.455), stdev = 0.015
  CI (99.9%): [2.159, 2.723] (assumes normal distribution)


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.004 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.443, 2.458, 2.469), stdev = 0.013
  CI (99.9%): [2.216, 2.700] (assumes normal distribution)


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
# Warmup Iteration   1: 4.473 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.004 ms/op
Iteration   1: 2.950 ±(99.9%) 0.004 ms/op
Iteration   2: 2.946 ±(99.9%) 0.005 ms/op
Iteration   3: 2.937 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.945 ±(99.9%) 0.123 ms/op [Average]
  (min, avg, max) = (2.937, 2.945, 2.950), stdev = 0.007
  CI (99.9%): [2.821, 3.068] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.964 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 13.921 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  6.253 ms/op
                 createUser·p0.9999: 12.174 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.650 ms/op
                 createUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385667
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 189160 
    [ 2.500,  3.750) = 191720 
    [ 3.750,  5.000) = 3778 
    [ 5.000,  6.250) = 467 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      9.131 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.400 ms/op
                 existUser·p0.999:  8.790 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.274 ms/op
                 existUser·p0.9999: 14.204 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  7.334 ms/op
                 existUser·p0.9999: 11.911 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391426
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 195291 
    [ 2.500,  3.750) = 193747 
    [ 3.750,  5.000) = 1752 
    [ 5.000,  6.250) = 185 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.449 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     13.777 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  11.990 ms/op
                 getUser·p0.9999: 14.245 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  7.876 ms/op
                 getUser·p0.9999: 14.077 ms/op
                 getUser·p1.00:   15.548 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.172 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  8.501 ms/op
                 getUser·p0.9999: 12.927 ms/op
                 getUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384295
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 190296 
    [ 2.500,  3.750) = 189734 
    [ 3.750,  5.000) = 3378 
    [ 5.000,  6.250) = 402 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 138 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.459 ms/op
     p(99.9900) =     13.926 ms/op
     p(99.9990) =     14.718 ms/op
     p(99.9999) =     15.548 ms/op
    p(100.0000) =     15.548 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.009 ms/op
Iteration   1: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.649 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.737 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.731 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.353 ms/op
                 listUser·p1.00:   10.797 ms/op

Iteration   3: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.551 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 12.121 ms/op
                 listUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322019
  mean =      2.978 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 97379 
    [ 2.500,  3.750) = 187541 
    [ 3.750,  5.000) = 30092 
    [ 5.000,  6.250) = 5669 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.400 ms/op
     p(99.9990) =     12.637 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.628 ± 1.231  ops/ms
ClientPb.existUser                       thrpt       3  13.140 ± 0.173  ops/ms
ClientPb.getUser                         thrpt       3  12.963 ± 1.589  ops/ms
ClientPb.listUser                        thrpt       3  10.855 ± 0.637  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.408   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.282   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.242   ms/op
ClientPb.listUser                         avgt       3   2.945 ± 0.123   ms/op
ClientPb.createUser                     sample  385667   2.487 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.531           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.131           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.533           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.713           ms/op
ClientPb.existUser                      sample  391426   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.884           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.777           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.828           ms/op
ClientPb.getUser                        sample  384295   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.935           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.459           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.926           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.548           ms/op
ClientPb.listUser                       sample  322019   2.978 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.400           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.124           ms/op
