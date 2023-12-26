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
# Warmup Iteration   1: 4.859 ops/ms
# Warmup Iteration   2: 12.055 ops/ms
# Warmup Iteration   3: 12.347 ops/ms
Iteration   1: 12.637 ops/ms
Iteration   2: 12.622 ops/ms
Iteration   3: 12.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.688 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (12.622, 12.688, 12.804), stdev = 0.101
  CI (99.9%): [10.838, 14.537] (assumes normal distribution)


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
# Warmup Iteration   1: 8.600 ops/ms
# Warmup Iteration   2: 13.108 ops/ms
# Warmup Iteration   3: 13.042 ops/ms
Iteration   1: 13.103 ops/ms
Iteration   2: 13.094 ops/ms
Iteration   3: 13.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.113 ±(99.9%) 0.476 ops/ms [Average]
  (min, avg, max) = (13.094, 13.113, 13.143), stdev = 0.026
  CI (99.9%): [12.638, 13.589] (assumes normal distribution)


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
# Warmup Iteration   1: 7.916 ops/ms
# Warmup Iteration   2: 12.320 ops/ms
# Warmup Iteration   3: 12.607 ops/ms
Iteration   1: 12.744 ops/ms
Iteration   2: 12.661 ops/ms
Iteration   3: 12.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.635 ±(99.9%) 2.245 ops/ms [Average]
  (min, avg, max) = (12.501, 12.635, 12.744), stdev = 0.123
  CI (99.9%): [10.390, 14.880] (assumes normal distribution)


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
# Warmup Iteration   1: 6.905 ops/ms
# Warmup Iteration   2: 10.434 ops/ms
# Warmup Iteration   3: 10.573 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.611 ops/ms
Iteration   3: 10.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.648 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (10.611, 10.648, 10.688), stdev = 0.038
  CI (99.9%): [9.949, 11.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.566 ±(99.9%) 0.004 ms/op
Iteration   2: 2.592 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.555, 2.571, 2.592), stdev = 0.019
  CI (99.9%): [2.219, 2.923] (assumes normal distribution)


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.449, 2.465, 2.485), stdev = 0.019
  CI (99.9%): [2.124, 2.806] (assumes normal distribution)


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.003 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.523 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.512, 2.523, 2.535), stdev = 0.011
  CI (99.9%): [2.315, 2.731] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.004 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.973 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (2.969, 2.973, 2.980), stdev = 0.006
  CI (99.9%): [2.860, 3.086] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  11.137 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.926 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 12.470 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  9.036 ms/op
                 createUser·p0.9999: 10.880 ms/op
                 createUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382463
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185662 
    [ 2.500,  3.750) = 192563 
    [ 3.750,  5.000) = 3335 
    [ 5.000,  6.250) = 310 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 175 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      9.675 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     14.164 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.804 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 15.794 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  8.439 ms/op
                 existUser·p0.9999: 13.700 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.497 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  7.343 ms/op
                 existUser·p0.9999: 15.156 ms/op
                 existUser·p1.00:   15.417 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388983
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 193269 
    [ 2.500,  3.750) = 191378 
    [ 3.750,  5.000) = 3480 
    [ 5.000,  6.250) = 412 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      6.538 ms/op
     p(99.9900) =     15.242 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.600 ms/op
                 getUser·p0.999:  10.515 ms/op
                 getUser·p0.9999: 13.703 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   2.613 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  9.515 ms/op
                 getUser·p0.9999: 15.645 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  8.399 ms/op
                 getUser·p0.9999: 11.750 ms/op
                 getUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379575
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 185133 
    [ 2.500,  3.750) = 189428 
    [ 3.750,  5.000) = 3747 
    [ 5.000,  6.250) = 745 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      8.592 ms/op
     p(99.9900) =     14.080 ms/op
     p(99.9990) =     15.863 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.462 ms/op
                 listUser·p0.99:   5.737 ms/op
                 listUser·p0.999:  8.983 ms/op
                 listUser·p0.9999: 11.403 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.725 ms/op
                 listUser·p0.9999: 10.819 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 13.278 ms/op
                 listUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318135
  mean =      3.015 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 93606 
    [ 2.500,  3.750) = 184367 
    [ 3.750,  5.000) = 32631 
    [ 5.000,  6.250) = 6120 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 182 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.615 ms/op
     p(99.9900) =     12.235 ms/op
     p(99.9990) =     13.448 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.688 ± 1.850  ops/ms
ClientPb.existUser                       thrpt       3  13.113 ± 0.476  ops/ms
ClientPb.getUser                         thrpt       3  12.635 ± 2.245  ops/ms
ClientPb.listUser                        thrpt       3  10.648 ± 0.699  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.352   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.341   ms/op
ClientPb.getUser                          avgt       3   2.523 ± 0.208   ms/op
ClientPb.listUser                         avgt       3   2.973 ± 0.113   ms/op
ClientPb.createUser                     sample  382463   2.507 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.896           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.675           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.926           ms/op
ClientPb.existUser                      sample  388983   2.465 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.538           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.242           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.482           ms/op
ClientPb.getUser                        sample  379575   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.918           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.592           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.080           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.942           ms/op
ClientPb.listUser                       sample  318135   3.015 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.700           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.615           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.566           ms/op
