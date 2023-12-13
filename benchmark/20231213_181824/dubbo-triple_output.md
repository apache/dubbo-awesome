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
# Warmup Iteration   1: 4.962 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.454 ops/ms
Iteration   1: 12.552 ops/ms
Iteration   2: 12.683 ops/ms
Iteration   3: 12.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.657 ±(99.9%) 1.726 ops/ms [Average]
  (min, avg, max) = (12.552, 12.657, 12.735), stdev = 0.095
  CI (99.9%): [10.930, 14.383] (assumes normal distribution)


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
# Warmup Iteration   1: 8.132 ops/ms
# Warmup Iteration   2: 13.003 ops/ms
# Warmup Iteration   3: 12.906 ops/ms
Iteration   1: 13.001 ops/ms
Iteration   2: 13.132 ops/ms
Iteration   3: 13.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.073 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (13.001, 13.073, 13.132), stdev = 0.067
  CI (99.9%): [11.859, 14.287] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.282 ops/ms
# Warmup Iteration   3: 12.515 ops/ms
Iteration   1: 12.368 ops/ms
Iteration   2: 12.690 ops/ms
Iteration   3: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.582 ±(99.9%) 3.375 ops/ms [Average]
  (min, avg, max) = (12.368, 12.582, 12.690), stdev = 0.185
  CI (99.9%): [9.207, 15.956] (assumes normal distribution)


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
# Warmup Iteration   1: 6.788 ops/ms
# Warmup Iteration   2: 10.472 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.710 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (10.646, 10.710, 10.757), stdev = 0.057
  CI (99.9%): [9.663, 11.757] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.533 ±(99.9%) 0.004 ms/op
Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
Iteration   3: 2.589 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.533, 2.570, 2.589), stdev = 0.032
  CI (99.9%): [1.989, 3.151] (assumes normal distribution)


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.489 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.477, 2.489, 2.499), stdev = 0.011
  CI (99.9%): [2.294, 2.683] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
Iteration   3: 2.517 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.532 ±(99.9%) 0.395 ms/op [Average]
  (min, avg, max) = (2.517, 2.532, 2.557), stdev = 0.022
  CI (99.9%): [2.137, 2.927] (assumes normal distribution)


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
# Warmup Iteration   1: 4.664 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
Iteration   1: 3.027 ±(99.9%) 0.005 ms/op
Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
Iteration   3: 3.025 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.015, 3.022, 3.027), stdev = 0.007
  CI (99.9%): [2.899, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  10.691 ms/op
                 createUser·p0.9999: 13.717 ms/op
                 createUser·p1.00:   14.418 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  7.475 ms/op
                 createUser·p0.9999: 12.194 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  7.096 ms/op
                 createUser·p0.9999: 11.487 ms/op
                 createUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386608
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 188917 
    [ 2.500,  3.750) = 192333 
    [ 3.750,  5.000) = 4298 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      7.756 ms/op
     p(99.9900) =     13.359 ms/op
     p(99.9990) =     14.098 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  8.054 ms/op
                 existUser·p0.9999: 13.847 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  8.525 ms/op
                 existUser·p0.9999: 12.406 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.558 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382617
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 185385 
    [ 2.500,  3.750) = 193376 
    [ 3.750,  5.000) = 2823 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      7.582 ms/op
     p(99.9900) =     13.414 ms/op
     p(99.9990) =     14.443 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.006 ms/op
Iteration   1: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.860 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 17.572 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.915 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  9.404 ms/op
                 getUser·p0.9999: 13.308 ms/op
                 getUser·p1.00:   14.303 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 12.619 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381721
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 187396 
    [ 2.500,  3.750) = 189601 
    [ 3.750,  5.000) = 3847 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      9.282 ms/op
     p(99.9900) =     16.056 ms/op
     p(99.9990) =     18.294 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 15.342 ms/op
                 listUser·p1.00:   16.056 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.627 ms/op
                 listUser·p0.9999: 15.372 ms/op
                 listUser·p1.00:   16.286 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317578
  mean =      3.020 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 90067 
    [ 2.500,  3.750) = 188422 
    [ 3.750,  5.000) = 31980 
    [ 5.000,  6.250) = 5687 
    [ 6.250,  7.500) = 660 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 218 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     14.930 ms/op
     p(99.9990) =     16.189 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.657 ± 1.726  ops/ms
ClientPb.existUser                       thrpt       3  13.073 ± 1.214  ops/ms
ClientPb.getUser                         thrpt       3  12.582 ± 3.375  ops/ms
ClientPb.listUser                        thrpt       3  10.710 ± 1.047  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.581   ms/op
ClientPb.existUser                        avgt       3   2.489 ± 0.195   ms/op
ClientPb.getUser                          avgt       3   2.532 ± 0.395   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 0.124   ms/op
ClientPb.createUser                     sample  386608   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.788           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.756           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.359           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.418           ms/op
ClientPb.existUser                      sample  382617   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.450           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.593           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.582           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.414           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.533           ms/op
ClientPb.getUser                        sample  381721   2.513 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.282           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.056           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.776           ms/op
ClientPb.listUser                       sample  317578   3.020 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.885           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.699           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.930           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.286           ms/op
