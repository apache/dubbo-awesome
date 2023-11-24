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
# Warmup Iteration   1: 5.074 ops/ms
# Warmup Iteration   2: 12.065 ops/ms
# Warmup Iteration   3: 12.181 ops/ms
Iteration   1: 12.552 ops/ms
Iteration   2: 12.657 ops/ms
Iteration   3: 12.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.631 ±(99.9%) 1.266 ops/ms [Average]
  (min, avg, max) = (12.552, 12.631, 12.683), stdev = 0.069
  CI (99.9%): [11.365, 13.897] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.482 ops/ms
# Warmup Iteration   2: 13.261 ops/ms
# Warmup Iteration   3: 13.181 ops/ms
Iteration   1: 13.288 ops/ms
Iteration   2: 13.311 ops/ms
Iteration   3: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.282 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (13.247, 13.282, 13.311), stdev = 0.032
  CI (99.9%): [12.691, 13.873] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.318 ops/ms
# Warmup Iteration   2: 12.791 ops/ms
# Warmup Iteration   3: 13.008 ops/ms
Iteration   1: 13.081 ops/ms
Iteration   2: 12.924 ops/ms
Iteration   3: 12.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.996 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (12.924, 12.996, 13.081), stdev = 0.079
  CI (99.9%): [11.549, 14.443] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.977 ops/ms
# Warmup Iteration   2: 10.603 ops/ms
# Warmup Iteration   3: 10.642 ops/ms
Iteration   1: 10.598 ops/ms
Iteration   2: 10.523 ops/ms
Iteration   3: 10.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.548 ±(99.9%) 0.801 ops/ms [Average]
  (min, avg, max) = (10.521, 10.548, 10.598), stdev = 0.044
  CI (99.9%): [9.746, 11.349] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.004 ms/op
Iteration   1: 2.576 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (2.501, 2.528, 2.576), stdev = 0.042
  CI (99.9%): [1.762, 3.294] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.561 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.003 ms/op
Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
Iteration   3: 2.447 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.446 ±(99.9%) 0.056 ms/op [Average]
  (min, avg, max) = (2.442, 2.446, 2.448), stdev = 0.003
  CI (99.9%): [2.390, 2.502] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.067 ms/op [Average]
  (min, avg, max) = (2.481, 2.485, 2.488), stdev = 0.004
  CI (99.9%): [2.419, 2.552] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.004 ms/op
Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
Iteration   3: 2.970 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.988 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (2.970, 2.988, 3.013), stdev = 0.023
  CI (99.9%): [2.575, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.672 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.564 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  12.288 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.643 ms/op
                 createUser·p0.999:  9.450 ms/op
                 createUser·p0.9999: 13.074 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.798 ms/op
                 createUser·p0.9999: 11.886 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376886
  mean =      2.545 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181582 
    [ 2.500,  5.000) = 194174 
    [ 5.000,  7.500) = 691 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     24.747 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  5.819 ms/op
                 existUser·p0.9999: 13.812 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  5.665 ms/op
                 existUser·p0.9999: 12.833 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  6.982 ms/op
                 existUser·p0.9999: 11.959 ms/op
                 existUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388531
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 193121 
    [ 2.500,  3.750) = 191919 
    [ 3.750,  5.000) = 2663 
    [ 5.000,  6.250) = 396 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      6.057 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     14.059 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
Iteration   1: 2.421 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.433 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  6.087 ms/op
                 getUser·p0.9999: 14.273 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  7.631 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  7.698 ms/op
                 getUser·p0.9999: 11.476 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390542
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 199509 
    [ 2.500,  3.750) = 187036 
    [ 3.750,  5.000) = 3252 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      7.271 ms/op
     p(99.9900) =     13.680 ms/op
     p(99.9990) =     14.601 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.699 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 12.062 ms/op
                 listUser·p1.00:   12.452 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 10.928 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  10.879 ms/op
                 listUser·p0.9999: 18.586 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317171
  mean =      3.024 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91629 
    [ 2.500,  5.000) = 217524 
    [ 5.000,  7.500) = 7313 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.238 ms/op
     p(99.9900) =     15.894 ms/op
     p(99.9990) =     19.545 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.631 ± 1.266  ops/ms
ClientPb.existUser                       thrpt       3  13.282 ± 0.591  ops/ms
ClientPb.getUser                         thrpt       3  12.996 ± 1.447  ops/ms
ClientPb.listUser                        thrpt       3  10.548 ± 0.801  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.766   ms/op
ClientPb.existUser                        avgt       3   2.446 ± 0.056   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.067   ms/op
ClientPb.listUser                         avgt       3   2.988 ± 0.413   ms/op
ClientPb.createUser                     sample  376886   2.545 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.833           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.882           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.909           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.035           ms/op
ClientPb.existUser                      sample  388531   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.758           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.517           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  390542   2.456 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.845           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.271           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  317171   3.024 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.895           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.894           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.316           ms/op
