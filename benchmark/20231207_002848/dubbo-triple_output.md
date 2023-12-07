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
# Warmup Iteration   1: 4.754 ops/ms
# Warmup Iteration   2: 12.302 ops/ms
# Warmup Iteration   3: 12.351 ops/ms
Iteration   1: 12.728 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.750 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (12.728, 12.750, 12.778), stdev = 0.025
  CI (99.9%): [12.289, 13.211] (assumes normal distribution)


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
# Warmup Iteration   1: 8.187 ops/ms
# Warmup Iteration   2: 13.087 ops/ms
# Warmup Iteration   3: 13.308 ops/ms
Iteration   1: 13.273 ops/ms
Iteration   2: 13.358 ops/ms
Iteration   3: 13.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.228 ±(99.9%) 2.864 ops/ms [Average]
  (min, avg, max) = (13.053, 13.228, 13.358), stdev = 0.157
  CI (99.9%): [10.364, 16.092] (assumes normal distribution)


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
# Warmup Iteration   1: 7.810 ops/ms
# Warmup Iteration   2: 12.493 ops/ms
# Warmup Iteration   3: 12.784 ops/ms
Iteration   1: 12.956 ops/ms
Iteration   2: 12.857 ops/ms
Iteration   3: 12.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.888 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (12.852, 12.888, 12.956), stdev = 0.058
  CI (99.9%): [11.822, 13.955] (assumes normal distribution)


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
# Warmup Iteration   1: 6.667 ops/ms
# Warmup Iteration   2: 10.449 ops/ms
# Warmup Iteration   3: 10.709 ops/ms
Iteration   1: 10.791 ops/ms
Iteration   2: 10.751 ops/ms
Iteration   3: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.763 ±(99.9%) 0.453 ops/ms [Average]
  (min, avg, max) = (10.746, 10.763, 10.791), stdev = 0.025
  CI (99.9%): [10.310, 11.215] (assumes normal distribution)


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.006 ms/op
Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
Iteration   3: 2.476 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.502 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (2.476, 2.502, 2.543), stdev = 0.036
  CI (99.9%): [1.852, 3.152] (assumes normal distribution)


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.414 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.403 ±(99.9%) 0.003 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
Iteration   3: 2.399 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.406 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.399, 2.406, 2.412), stdev = 0.007
  CI (99.9%): [2.282, 2.531] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.509 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.506, 2.509, 2.514), stdev = 0.004
  CI (99.9%): [2.428, 2.591] (assumes normal distribution)


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
# Warmup Iteration   1: 4.776 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.007 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.982 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.977, 2.982, 2.985), stdev = 0.004
  CI (99.9%): [2.911, 3.053] (assumes normal distribution)


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.748 ms/op
                 createUser·p0.999:  11.764 ms/op
                 createUser·p0.9999: 13.833 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.551 ms/op
                 createUser·p0.999:  7.583 ms/op
                 createUser·p0.9999: 12.093 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  9.184 ms/op
                 createUser·p0.9999: 14.737 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386295
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 185864 
    [ 2.500,  3.750) = 196913 
    [ 3.750,  5.000) = 2670 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      9.481 ms/op
     p(99.9900) =     13.528 ms/op
     p(99.9990) =     17.909 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.665 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.412 ms/op
                 existUser·p0.999:  4.899 ms/op
                 existUser·p0.9999: 13.547 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  7.593 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.631 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.518 ms/op
                 existUser·p0.999:  5.902 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394641
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 195367 
    [ 2.500,  3.750) = 196910 
    [ 3.750,  5.000) = 1762 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      5.980 ms/op
     p(99.9900) =     13.133 ms/op
     p(99.9990) =     14.422 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  6.114 ms/op
                 getUser·p0.9999: 13.172 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.739 ms/op
                 getUser·p0.999:  6.932 ms/op
                 getUser·p0.9999: 12.664 ms/op
                 getUser·p1.00:   13.287 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  6.661 ms/op
                 getUser·p0.9999: 11.698 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390864
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 198357 
    [ 2.500,  3.750) = 187990 
    [ 3.750,  5.000) = 3511 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 152 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      6.618 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.341 ms/op
     p(99.9999) =     13.500 ms/op
    p(100.0000) =     13.500 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 2.979 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.941 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.606 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.441 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.068 ms/op
                 listUser·p0.9999: 10.965 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.195 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321893
  mean =      2.979 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 98439 
    [ 2.500,  3.750) = 186172 
    [ 3.750,  5.000) = 30228 
    [ 5.000,  6.250) = 5613 
    [ 6.250,  7.500) = 631 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 359 
    [10.000, 11.250) = 146 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.105 ms/op
     p(99.9990) =     12.345 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.750 ± 0.461  ops/ms
ClientPb.existUser                       thrpt       3  13.228 ± 2.864  ops/ms
ClientPb.getUser                         thrpt       3  12.888 ± 1.066  ops/ms
ClientPb.listUser                        thrpt       3  10.763 ± 0.453  ops/ms
ClientPb.createUser                       avgt       3   2.502 ± 0.650   ms/op
ClientPb.existUser                        avgt       3   2.406 ± 0.125   ms/op
ClientPb.getUser                          avgt       3   2.509 ± 0.081   ms/op
ClientPb.listUser                         avgt       3   2.982 ± 0.071   ms/op
ClientPb.createUser                     sample  386295   2.483 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.688           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.481           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.528           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.071           ms/op
ClientPb.existUser                      sample  394641   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.828           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.980           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.057           ms/op
ClientPb.getUser                        sample  390864   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.642           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.618           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.993           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.500           ms/op
ClientPb.listUser                       sample  321893   2.979 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.909           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.105           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
