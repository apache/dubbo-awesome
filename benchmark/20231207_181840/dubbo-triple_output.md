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
# Warmup Iteration   1: 4.873 ops/ms
# Warmup Iteration   2: 12.174 ops/ms
# Warmup Iteration   3: 12.378 ops/ms
Iteration   1: 12.654 ops/ms
Iteration   2: 12.810 ops/ms
Iteration   3: 12.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.794 ±(99.9%) 2.420 ops/ms [Average]
  (min, avg, max) = (12.654, 12.794, 12.918), stdev = 0.133
  CI (99.9%): [10.374, 15.214] (assumes normal distribution)


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
# Warmup Iteration   1: 8.134 ops/ms
# Warmup Iteration   2: 13.215 ops/ms
# Warmup Iteration   3: 13.202 ops/ms
Iteration   1: 13.395 ops/ms
Iteration   2: 13.352 ops/ms
Iteration   3: 13.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.329 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (13.240, 13.329, 13.395), stdev = 0.080
  CI (99.9%): [11.876, 14.782] (assumes normal distribution)


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
# Warmup Iteration   1: 7.773 ops/ms
# Warmup Iteration   2: 12.712 ops/ms
# Warmup Iteration   3: 12.688 ops/ms
Iteration   1: 12.937 ops/ms
Iteration   2: 12.701 ops/ms
Iteration   3: 12.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.838 ±(99.9%) 2.240 ops/ms [Average]
  (min, avg, max) = (12.701, 12.838, 12.937), stdev = 0.123
  CI (99.9%): [10.599, 15.078] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.802 ops/ms
# Warmup Iteration   2: 10.310 ops/ms
# Warmup Iteration   3: 10.750 ops/ms
Iteration   1: 10.654 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.696 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (10.654, 10.696, 10.722), stdev = 0.037
  CI (99.9%): [10.028, 11.363] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.485 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.476, 2.485, 2.497), stdev = 0.011
  CI (99.9%): [2.286, 2.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.003 ms/op
Iteration   3: 2.496 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.530 ms/op [Average]
  (min, avg, max) = (2.444, 2.478, 2.496), stdev = 0.029
  CI (99.9%): [1.948, 3.008] (assumes normal distribution)


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.427 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.446 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.427, 2.446, 2.467), stdev = 0.020
  CI (99.9%): [2.075, 2.816] (assumes normal distribution)


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.945 ±(99.9%) 0.006 ms/op
Iteration   2: 2.962 ±(99.9%) 0.005 ms/op
Iteration   3: 2.944 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.950 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (2.944, 2.950, 2.962), stdev = 0.010
  CI (99.9%): [2.771, 3.129] (assumes normal distribution)


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.942 ms/op
                 createUser·p0.9999: 13.896 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  8.695 ms/op
                 createUser·p0.9999: 12.861 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.409 ms/op
                 createUser·p0.9999: 10.011 ms/op
                 createUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385925
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 188187 
    [ 2.500,  3.750) = 193782 
    [ 3.750,  5.000) = 3009 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.391 ms/op
     p(99.9900) =     13.114 ms/op
     p(99.9990) =     14.027 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  5.915 ms/op
                 existUser·p0.9999: 13.648 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.709 ms/op
                 existUser·p0.9999: 12.662 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  8.503 ms/op
                 existUser·p0.9999: 11.589 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396608
  mean =      2.418 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 199148 
    [ 2.500,  3.750) = 193942 
    [ 3.750,  5.000) = 2716 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 122 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      6.001 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.142 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  7.952 ms/op
                 getUser·p0.9999: 13.683 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  10.057 ms/op
                 getUser·p0.9999: 13.633 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.400 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  7.156 ms/op
                 getUser·p0.9999: 11.368 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389355
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 201545 
    [ 2.500,  3.750) = 182634 
    [ 3.750,  5.000) = 3991 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.437 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     13.452 ms/op
     p(99.9990) =     14.102 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.009 ms/op
Iteration   1: 2.963 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 11.079 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   2: 2.959 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.010 ms/op
                 listUser·p0.9999: 10.420 ms/op
                 listUser·p1.00:   11.092 ms/op

Iteration   3: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.073 ms/op
                 listUser·p0.9999: 11.049 ms/op
                 listUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324117
  mean =      2.959 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 101280 
    [ 2.500,  3.750) = 186881 
    [ 3.750,  5.000) = 28849 
    [ 5.000,  6.250) = 5621 
    [ 6.250,  7.500) = 645 
    [ 7.500,  8.750) = 315 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      8.993 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     11.743 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.794 ± 2.420  ops/ms
ClientPb.existUser                       thrpt       3  13.329 ± 1.453  ops/ms
ClientPb.getUser                         thrpt       3  12.838 ± 2.240  ops/ms
ClientPb.listUser                        thrpt       3  10.696 ± 0.667  ops/ms
ClientPb.createUser                       avgt       3   2.485 ± 0.198   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.530   ms/op
ClientPb.getUser                          avgt       3   2.446 ± 0.371   ms/op
ClientPb.listUser                         avgt       3   2.950 ± 0.179   ms/op
ClientPb.createUser                     sample  385925   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.756           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.391           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.114           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.107           ms/op
ClientPb.existUser                      sample  396608   2.418 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.921           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.001           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.156           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  389355   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.634           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.651           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.452           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.303           ms/op
ClientPb.listUser                       sample  324117   2.959 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.946           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.993           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.781           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.157           ms/op
