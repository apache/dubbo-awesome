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
# Warmup Iteration   1: 5.038 ops/ms
# Warmup Iteration   2: 12.260 ops/ms
# Warmup Iteration   3: 12.611 ops/ms
Iteration   1: 12.788 ops/ms
Iteration   2: 12.906 ops/ms
Iteration   3: 12.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.850 ±(99.9%) 1.081 ops/ms [Average]
  (min, avg, max) = (12.788, 12.850, 12.906), stdev = 0.059
  CI (99.9%): [11.770, 13.931] (assumes normal distribution)


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
# Warmup Iteration   1: 7.941 ops/ms
# Warmup Iteration   2: 13.198 ops/ms
# Warmup Iteration   3: 13.088 ops/ms
Iteration   1: 13.145 ops/ms
Iteration   2: 13.151 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.131 ±(99.9%) 0.543 ops/ms [Average]
  (min, avg, max) = (13.097, 13.131, 13.151), stdev = 0.030
  CI (99.9%): [12.588, 13.674] (assumes normal distribution)


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
# Warmup Iteration   1: 7.827 ops/ms
# Warmup Iteration   2: 12.747 ops/ms
# Warmup Iteration   3: 12.783 ops/ms
Iteration   1: 12.883 ops/ms
Iteration   2: 12.851 ops/ms
Iteration   3: 12.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.911 ±(99.9%) 1.420 ops/ms [Average]
  (min, avg, max) = (12.851, 12.911, 12.999), stdev = 0.078
  CI (99.9%): [11.491, 14.331] (assumes normal distribution)


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
# Warmup Iteration   1: 6.872 ops/ms
# Warmup Iteration   2: 10.449 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.589 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (10.509, 10.589, 10.647), stdev = 0.071
  CI (99.9%): [9.285, 11.892] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.003 ms/op
Iteration   1: 2.497 ±(99.9%) 0.003 ms/op
Iteration   2: 2.510 ±(99.9%) 0.003 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.497, 2.502, 2.510), stdev = 0.007
  CI (99.9%): [2.380, 2.624] (assumes normal distribution)


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.004 ms/op
Iteration   1: 2.432 ±(99.9%) 0.004 ms/op
Iteration   2: 2.436 ±(99.9%) 0.004 ms/op
Iteration   3: 2.411 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.411, 2.426, 2.436), stdev = 0.014
  CI (99.9%): [2.176, 2.677] (assumes normal distribution)


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.464 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.453, 2.464, 2.475), stdev = 0.011
  CI (99.9%): [2.262, 2.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.062 ms/op [Average]
  (min, avg, max) = (2.983, 2.987, 2.990), stdev = 0.003
  CI (99.9%): [2.924, 3.049] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.848 ms/op
                 createUser·p0.999:  10.023 ms/op
                 createUser·p0.9999: 14.413 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.576 ms/op
                 createUser·p0.999:  5.626 ms/op
                 createUser·p0.9999: 12.142 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  8.067 ms/op
                 createUser·p0.9999: 10.437 ms/op
                 createUser·p1.00:   11.289 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386697
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 190195 
    [ 2.500,  3.750) = 192692 
    [ 3.750,  5.000) = 2910 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      9.037 ms/op
     p(99.9900) =     13.549 ms/op
     p(99.9990) =     15.407 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.305 ms/op
                 existUser·p0.999:  5.270 ms/op
                 existUser·p0.9999: 13.255 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  6.186 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.057 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  8.418 ms/op
                 existUser·p0.9999: 11.831 ms/op
                 existUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393963
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 195697 
    [ 2.500,  3.750) = 196026 
    [ 3.750,  5.000) = 1537 
    [ 5.000,  6.250) = 289 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      3.422 ms/op
     p(99.9000) =      6.005 ms/op
     p(99.9900) =     13.150 ms/op
     p(99.9990) =     13.898 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.464 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  6.580 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  6.649 ms/op
                 getUser·p0.9999: 12.652 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  7.468 ms/op
                 getUser·p0.9999: 15.944 ms/op
                 getUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388436
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 193953 
    [ 2.500,  3.750) = 189242 
    [ 3.750,  5.000) = 4199 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      6.665 ms/op
     p(99.9900) =     16.430 ms/op
     p(99.9990) =     19.206 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.648 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.009 ms/op
Iteration   1: 2.978 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.052 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.379 ms/op
                 listUser·p1.00:   11.239 ms/op

Iteration   3: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.817 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 10.895 ms/op
                 listUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322158
  mean =      2.977 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 98278 
    [ 2.500,  3.750) = 186619 
    [ 3.750,  5.000) = 30268 
    [ 5.000,  6.250) = 5525 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.525 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     11.565 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.850 ± 1.081  ops/ms
ClientPb.existUser                       thrpt       3  13.131 ± 0.543  ops/ms
ClientPb.getUser                         thrpt       3  12.911 ± 1.420  ops/ms
ClientPb.listUser                        thrpt       3  10.589 ± 1.303  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.122   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.250   ms/op
ClientPb.getUser                          avgt       3   2.464 ± 0.202   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.062   ms/op
ClientPb.createUser                     sample  386697   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.037           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.549           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.794           ms/op
ClientPb.existUser                      sample  393963   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.422           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.150           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  388436   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.724           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.665           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.430           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.366           ms/op
ClientPb.listUser                       sample  322158   2.977 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.525           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.011           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.895           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.009           ms/op
