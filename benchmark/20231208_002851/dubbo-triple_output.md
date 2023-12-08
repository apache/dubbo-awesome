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
# Warmup Iteration   1: 5.185 ops/ms
# Warmup Iteration   2: 11.917 ops/ms
# Warmup Iteration   3: 12.329 ops/ms
Iteration   1: 12.595 ops/ms
Iteration   2: 12.931 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.787 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (12.595, 12.787, 12.931), stdev = 0.173
  CI (99.9%): [9.628, 15.946] (assumes normal distribution)


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
# Warmup Iteration   1: 8.017 ops/ms
# Warmup Iteration   2: 13.252 ops/ms
# Warmup Iteration   3: 13.371 ops/ms
Iteration   1: 13.200 ops/ms
Iteration   2: 13.191 ops/ms
Iteration   3: 13.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.217 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (13.191, 13.217, 13.259), stdev = 0.037
  CI (99.9%): [12.539, 13.894] (assumes normal distribution)


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
# Warmup Iteration   1: 8.299 ops/ms
# Warmup Iteration   2: 12.539 ops/ms
# Warmup Iteration   3: 12.875 ops/ms
Iteration   1: 13.116 ops/ms
Iteration   2: 12.975 ops/ms
Iteration   3: 13.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.077 ±(99.9%) 1.629 ops/ms [Average]
  (min, avg, max) = (12.975, 13.077, 13.140), stdev = 0.089
  CI (99.9%): [11.448, 14.707] (assumes normal distribution)


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
# Warmup Iteration   1: 6.627 ops/ms
# Warmup Iteration   2: 10.450 ops/ms
# Warmup Iteration   3: 10.657 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.745 ops/ms
Iteration   3: 10.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.654 ±(99.9%) 2.294 ops/ms [Average]
  (min, avg, max) = (10.511, 10.654, 10.745), stdev = 0.126
  CI (99.9%): [8.360, 12.948] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.489, 2.506, 2.520), stdev = 0.016
  CI (99.9%): [2.215, 2.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.442 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.003 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.432 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.423, 2.432, 2.440), stdev = 0.009
  CI (99.9%): [2.276, 2.588] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.496 ±(99.9%) 0.003 ms/op
Iteration   3: 2.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.496, 2.502, 2.512), stdev = 0.009
  CI (99.9%): [2.338, 2.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.005 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
Iteration   3: 2.961 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (2.961, 2.992, 3.017), stdev = 0.028
  CI (99.9%): [2.475, 3.509] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  9.516 ms/op
                 createUser·p0.9999: 13.438 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  6.589 ms/op
                 createUser·p0.9999: 11.846 ms/op
                 createUser·p1.00:   12.141 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  7.522 ms/op
                 createUser·p0.9999: 11.158 ms/op
                 createUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387502
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 189015 
    [ 2.500,  3.750) = 194255 
    [ 3.750,  5.000) = 3450 
    [ 5.000,  6.250) = 281 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     13.693 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 3.743 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.809 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 13.384 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   3.310 ms/op
                 existUser·p0.999:  6.513 ms/op
                 existUser·p0.9999: 13.708 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.605 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 14.415 ms/op
                 existUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396041
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 194457 
    [ 2.500,  3.750) = 198019 
    [ 3.750,  5.000) = 2686 
    [ 5.000,  6.250) = 457 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.925 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      5.929 ms/op
     p(99.9900) =     14.048 ms/op
     p(99.9990) =     15.107 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  9.526 ms/op
                 getUser·p0.9999: 14.060 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  9.754 ms/op
                 getUser·p0.9999: 12.856 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 11.597 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380862
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 186530 
    [ 2.500,  3.750) = 187548 
    [ 3.750,  5.000) = 4969 
    [ 5.000,  6.250) = 1155 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.948 ms/op
     p(99.9900) =     13.724 ms/op
     p(99.9990) =     14.650 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 4.879 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 11.230 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   2: 3.022 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 11.246 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 12.241 ms/op
                 listUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317541
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 93483 
    [ 2.500,  3.750) = 184552 
    [ 3.750,  5.000) = 31749 
    [ 5.000,  6.250) = 6195 
    [ 6.250,  7.500) = 774 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 215 
    [10.000, 11.250) = 232 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     12.629 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.787 ± 3.159  ops/ms
ClientPb.existUser                       thrpt       3  13.217 ± 0.677  ops/ms
ClientPb.getUser                         thrpt       3  13.077 ± 1.629  ops/ms
ClientPb.listUser                        thrpt       3  10.654 ± 2.294  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.291   ms/op
ClientPb.existUser                        avgt       3   2.432 ± 0.156   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.163   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.517   ms/op
ClientPb.createUser                     sample  387502   2.475 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.724           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.845           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.894           ms/op
ClientPb.existUser                      sample  396041   2.421 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.809           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.925           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.929           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.048           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.401           ms/op
ClientPb.getUser                        sample  380862   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.785           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.948           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.926           ms/op
ClientPb.listUser                       sample  317541   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.863           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.518           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
