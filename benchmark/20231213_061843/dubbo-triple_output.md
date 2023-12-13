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
# Warmup Iteration   1: 4.734 ops/ms
# Warmup Iteration   2: 12.361 ops/ms
# Warmup Iteration   3: 12.441 ops/ms
Iteration   1: 12.631 ops/ms
Iteration   2: 12.839 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.780 ±(99.9%) 2.363 ops/ms [Average]
  (min, avg, max) = (12.631, 12.780, 12.869), stdev = 0.129
  CI (99.9%): [10.417, 15.142] (assumes normal distribution)


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
# Warmup Iteration   1: 8.559 ops/ms
# Warmup Iteration   2: 13.384 ops/ms
# Warmup Iteration   3: 13.437 ops/ms
Iteration   1: 13.372 ops/ms
Iteration   2: 13.490 ops/ms
Iteration   3: 13.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.420 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (13.372, 13.420, 13.490), stdev = 0.062
  CI (99.9%): [12.285, 14.555] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.121 ops/ms
# Warmup Iteration   2: 12.891 ops/ms
# Warmup Iteration   3: 12.878 ops/ms
Iteration   1: 13.048 ops/ms
Iteration   2: 13.043 ops/ms
Iteration   3: 13.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.064 ±(99.9%) 0.576 ops/ms [Average]
  (min, avg, max) = (13.043, 13.064, 13.100), stdev = 0.032
  CI (99.9%): [12.487, 13.640] (assumes normal distribution)


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
# Warmup Iteration   1: 6.487 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 10.472 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.674 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.685 ±(99.9%) 0.799 ops/ms [Average]
  (min, avg, max) = (10.649, 10.685, 10.734), stdev = 0.044
  CI (99.9%): [9.887, 11.484] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.003 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.497 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (2.478, 2.497, 2.529), stdev = 0.028
  CI (99.9%): [1.995, 2.999] (assumes normal distribution)


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (2.435, 2.441, 2.448), stdev = 0.007
  CI (99.9%): [2.312, 2.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.500 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.489, 2.500, 2.510), stdev = 0.011
  CI (99.9%): [2.307, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.748 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.001 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (2.986, 3.001, 3.017), stdev = 0.015
  CI (99.9%): [2.722, 3.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.170 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 13.799 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.478 ms/op
                 createUser·p0.999:  7.443 ms/op
                 createUser·p0.9999: 12.075 ms/op
                 createUser·p1.00:   12.370 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  9.133 ms/op
                 createUser·p0.9999: 12.194 ms/op
                 createUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386390
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 188873 
    [ 2.500,  3.750) = 194064 
    [ 3.750,  5.000) = 2541 
    [ 5.000,  6.250) = 374 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      9.136 ms/op
     p(99.9900) =     13.605 ms/op
     p(99.9990) =     14.027 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  5.835 ms/op
                 existUser·p0.9999: 13.873 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.730 ms/op
                 existUser·p0.999:  6.414 ms/op
                 existUser·p0.9999: 12.531 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  6.611 ms/op
                 existUser·p0.9999: 12.737 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396730
  mean =      2.417 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 199020 
    [ 2.500,  3.750) = 195032 
    [ 3.750,  5.000) = 1944 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =      6.398 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     13.944 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  7.493 ms/op
                 getUser·p0.9999: 13.567 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  8.956 ms/op
                 getUser·p0.9999: 13.830 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.306 ms/op
                 getUser·p0.9999: 11.668 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385754
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 192273 
    [ 2.500,  3.750) = 188042 
    [ 3.750,  5.000) = 3983 
    [ 5.000,  6.250) = 785 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      8.292 ms/op
     p(99.9900) =     13.465 ms/op
     p(99.9990) =     14.193 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.997 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.009 ms/op
Iteration   1: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.864 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.200 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.829 ms/op
                 listUser·p0.9999: 13.058 ms/op
                 listUser·p1.00:   15.729 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.654 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321026
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 95670 
    [ 2.500,  3.750) = 186664 
    [ 3.750,  5.000) = 31616 
    [ 5.000,  6.250) = 5585 
    [ 6.250,  7.500) = 645 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.453 ms/op
     p(99.9900) =     12.491 ms/op
     p(99.9990) =     13.585 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.780 ± 2.363  ops/ms
ClientPb.existUser                       thrpt       3  13.420 ± 1.135  ops/ms
ClientPb.getUser                         thrpt       3  13.064 ± 0.576  ops/ms
ClientPb.listUser                        thrpt       3  10.685 ± 0.799  ops/ms
ClientPb.createUser                       avgt       3   2.497 ± 0.502   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.128   ms/op
ClientPb.getUser                          avgt       3   2.500 ± 0.194   ms/op
ClientPb.listUser                         avgt       3   3.001 ± 0.279   ms/op
ClientPb.createUser                     sample  386390   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.136           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.605           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.678           ms/op
ClientPb.existUser                      sample  396730   2.417 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.502           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.304           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.696           ms/op
ClientPb.getUser                        sample  385754   2.486 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.880           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.292           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.465           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  321026   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.654           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.453           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.491           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.729           ms/op
