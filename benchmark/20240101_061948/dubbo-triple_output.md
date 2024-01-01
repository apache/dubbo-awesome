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
# Warmup Iteration   1: 5.224 ops/ms
# Warmup Iteration   2: 12.204 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.663 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.691 ±(99.9%) 0.592 ops/ms [Average]
  (min, avg, max) = (12.663, 12.691, 12.726), stdev = 0.032
  CI (99.9%): [12.099, 13.283] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.145 ops/ms
# Warmup Iteration   2: 13.068 ops/ms
# Warmup Iteration   3: 12.947 ops/ms
Iteration   1: 13.411 ops/ms
Iteration   2: 13.253 ops/ms
Iteration   3: 13.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.244 ±(99.9%) 3.134 ops/ms [Average]
  (min, avg, max) = (13.068, 13.244, 13.411), stdev = 0.172
  CI (99.9%): [10.110, 16.378] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.121 ops/ms
# Warmup Iteration   2: 12.747 ops/ms
# Warmup Iteration   3: 12.967 ops/ms
Iteration   1: 13.043 ops/ms
Iteration   2: 12.959 ops/ms
Iteration   3: 12.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.984 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (12.949, 12.984, 13.043), stdev = 0.052
  CI (99.9%): [12.034, 13.933] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.181 ops/ms
# Warmup Iteration   2: 10.560 ops/ms
# Warmup Iteration   3: 10.718 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.887 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.868 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (10.806, 10.868, 10.911), stdev = 0.055
  CI (99.9%): [9.868, 11.868] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.003 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.473 ±(99.9%) 0.146 ms/op [Average]
  (min, avg, max) = (2.468, 2.473, 2.482), stdev = 0.008
  CI (99.9%): [2.327, 2.619] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.005 ms/op
Iteration   2: 2.442 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.431, 2.439, 2.445), stdev = 0.007
  CI (99.9%): [2.313, 2.565] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.003 ms/op
Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.453, 2.476, 2.489), stdev = 0.020
  CI (99.9%): [2.108, 2.844] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
Iteration   1: 2.980 ±(99.9%) 0.006 ms/op
Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
Iteration   3: 2.949 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.963 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.949, 2.963, 2.980), stdev = 0.016
  CI (99.9%): [2.677, 3.249] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.527 ms/op
                 createUser·p0.999:  5.608 ms/op
                 createUser·p0.9999: 13.071 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  6.396 ms/op
                 createUser·p0.9999: 12.549 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 12.859 ms/op
                 createUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391891
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 193382 
    [ 2.500,  3.750) = 195686 
    [ 3.750,  5.000) = 2160 
    [ 5.000,  6.250) = 167 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      8.997 ms/op
     p(99.9900) =     12.842 ms/op
     p(99.9990) =     14.697 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.375 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  5.948 ms/op
                 existUser·p0.9999: 14.407 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.394 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  6.615 ms/op
                 existUser·p0.9999: 12.489 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  8.748 ms/op
                 existUser·p0.9999: 12.449 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399828
  mean =      2.398 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 207362 
    [ 2.500,  3.750) = 189114 
    [ 3.750,  5.000) = 2451 
    [ 5.000,  6.250) = 365 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 173 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      7.721 ms/op
     p(99.9900) =     12.895 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.551 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.671 ms/op
                 getUser·p0.999:  5.755 ms/op
                 getUser·p0.9999: 13.536 ms/op
                 getUser·p1.00:   14.385 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.879 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 12.403 ms/op
                 getUser·p1.00:   12.878 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.939 ms/op
                 getUser·p0.999:  8.196 ms/op
                 getUser·p0.9999: 10.924 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383088
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 190168 
    [ 2.500,  3.750) = 188617 
    [ 3.750,  5.000) = 3304 
    [ 5.000,  6.250) = 544 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.188 ms/op
     p(99.9900) =     13.151 ms/op
     p(99.9990) =     14.055 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
Iteration   1: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.182 ms/op
                 listUser·p1.00:   10.895 ms/op

Iteration   2: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.718 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.424 ms/op
                 listUser·p0.9999: 12.708 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324407
  mean =      2.957 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 102240 
    [ 2.500,  3.750) = 186006 
    [ 3.750,  5.000) = 29559 
    [ 5.000,  6.250) = 5341 
    [ 6.250,  7.500) = 490 
    [ 7.500,  8.750) = 211 
    [ 8.750, 10.000) = 271 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     11.434 ms/op
     p(99.9990) =     12.993 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.691 ± 0.592  ops/ms
ClientPb.existUser                       thrpt       3  13.244 ± 3.134  ops/ms
ClientPb.getUser                         thrpt       3  12.984 ± 0.950  ops/ms
ClientPb.listUser                        thrpt       3  10.868 ± 1.000  ops/ms
ClientPb.createUser                       avgt       3   2.473 ± 0.146   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.126   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.368   ms/op
ClientPb.listUser                         avgt       3   2.963 ± 0.286   ms/op
ClientPb.createUser                     sample  391891   2.447 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.850           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.966           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.997           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.842           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  399828   2.398 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.752           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.445           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.721           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.895           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.172           ms/op
ClientPb.getUser                        sample  383088   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.551           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.188           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.151           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.385           ms/op
ClientPb.listUser                       sample  324407   2.957 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.434           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
