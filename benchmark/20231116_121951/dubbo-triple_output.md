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
# Warmup Iteration   1: 4.649 ops/ms
# Warmup Iteration   2: 11.993 ops/ms
# Warmup Iteration   3: 12.309 ops/ms
Iteration   1: 12.404 ops/ms
Iteration   2: 12.647 ops/ms
Iteration   3: 12.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.535 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (12.404, 12.535, 12.647), stdev = 0.123
  CI (99.9%): [10.299, 14.771] (assumes normal distribution)


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
# Warmup Iteration   1: 8.332 ops/ms
# Warmup Iteration   2: 12.898 ops/ms
# Warmup Iteration   3: 13.015 ops/ms
Iteration   1: 12.804 ops/ms
Iteration   2: 12.954 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.935 ±(99.9%) 2.241 ops/ms [Average]
  (min, avg, max) = (12.804, 12.935, 13.047), stdev = 0.123
  CI (99.9%): [10.694, 15.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.445 ops/ms
# Warmup Iteration   2: 12.658 ops/ms
# Warmup Iteration   3: 12.731 ops/ms
Iteration   1: 12.896 ops/ms
Iteration   2: 12.859 ops/ms
Iteration   3: 12.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.823 ±(99.9%) 1.761 ops/ms [Average]
  (min, avg, max) = (12.713, 12.823, 12.896), stdev = 0.097
  CI (99.9%): [11.061, 14.584] (assumes normal distribution)


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
# Warmup Iteration   1: 6.674 ops/ms
# Warmup Iteration   2: 10.444 ops/ms
# Warmup Iteration   3: 10.514 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.587 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.538 ±(99.9%) 1.356 ops/ms [Average]
  (min, avg, max) = (10.453, 10.538, 10.587), stdev = 0.074
  CI (99.9%): [9.182, 11.894] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.955 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.004 ms/op
Iteration   1: 2.534 ±(99.9%) 0.003 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.533 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.524, 2.533, 2.540), stdev = 0.008
  CI (99.9%): [2.389, 2.677] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.749 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.003 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.441, 2.457, 2.481), stdev = 0.021
  CI (99.9%): [2.075, 2.839] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.005 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.017 ms/op [Average]
  (min, avg, max) = (2.514, 2.515, 2.516), stdev = 0.001
  CI (99.9%): [2.498, 2.532] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.741 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
Iteration   3: 3.050 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.037 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (3.013, 3.037, 3.050), stdev = 0.021
  CI (99.9%): [2.658, 3.416] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.179 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.576 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.170 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 14.526 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.668 ms/op
                 createUser·p0.999:  10.201 ms/op
                 createUser·p0.9999: 13.637 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  8.712 ms/op
                 createUser·p0.9999: 10.376 ms/op
                 createUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378733
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 181664 
    [ 2.500,  3.750) = 192065 
    [ 3.750,  5.000) = 3897 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      8.741 ms/op
     p(99.9900) =     13.896 ms/op
     p(99.9990) =     14.719 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.900 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.769 ms/op
                 existUser·p0.999:  5.415 ms/op
                 existUser·p0.9999: 13.927 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  7.434 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  8.868 ms/op
                 existUser·p0.9999: 11.737 ms/op
                 existUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388351
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 189532 
    [ 2.500,  3.750) = 194219 
    [ 3.750,  5.000) = 3328 
    [ 5.000,  6.250) = 774 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.889 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     13.812 ms/op
     p(99.9990) =     14.852 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.595 ±(99.9%) 0.006 ms/op
Iteration   1: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  12.708 ms/op
                 getUser·p0.9999: 14.534 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   2: 2.571 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   2.605 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 14.713 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.010 ms/op
                 getUser·p0.999:  9.290 ms/op
                 getUser·p0.9999: 11.853 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374352
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 179947 
    [ 2.500,  3.750) = 188362 
    [ 3.750,  5.000) = 4647 
    [ 5.000,  6.250) = 772 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      9.907 ms/op
     p(99.9900) =     14.347 ms/op
     p(99.9990) =     15.357 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
Iteration   1: 3.076 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   6.078 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.514 ms/op
                 listUser·p0.9999: 11.373 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.391 ms/op
                 listUser·p0.9999: 10.909 ms/op
                 listUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312104
  mean =      3.073 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 81151 
    [ 2.500,  3.750) = 186368 
    [ 3.750,  5.000) = 36111 
    [ 5.000,  6.250) = 6664 
    [ 6.250,  7.500) = 1035 
    [ 7.500,  8.750) = 199 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 192 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =      9.468 ms/op
     p(99.9900) =     11.380 ms/op
     p(99.9990) =     12.053 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.535 ± 2.236  ops/ms
ClientPb.existUser                       thrpt       3  12.935 ± 2.241  ops/ms
ClientPb.getUser                         thrpt       3  12.823 ± 1.761  ops/ms
ClientPb.listUser                        thrpt       3  10.538 ± 1.356  ops/ms
ClientPb.createUser                       avgt       3   2.533 ± 0.144   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.382   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.017   ms/op
ClientPb.listUser                         avgt       3   3.037 ± 0.379   ms/op
ClientPb.createUser                     sample  378733   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.822           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.896           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.303           ms/op
ClientPb.existUser                      sample  388351   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.889           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.873           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.812           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.335           ms/op
ClientPb.getUser                        sample  374352   2.562 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.872           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.265           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.907           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.347           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.974           ms/op
ClientPb.listUser                       sample  312104   3.073 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.834           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.380           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.091           ms/op
