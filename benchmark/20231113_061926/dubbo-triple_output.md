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
# Warmup Iteration   1: 1.648 ops/ms
# Warmup Iteration   2: 3.823 ops/ms
# Warmup Iteration   3: 7.527 ops/ms
Iteration   1: 7.790 ops/ms
Iteration   2: 8.226 ops/ms
Iteration   3: 8.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.039 ±(99.9%) 4.099 ops/ms [Average]
  (min, avg, max) = (7.790, 8.039, 8.226), stdev = 0.225
  CI (99.9%): [3.940, 12.139] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.387 ops/ms
# Warmup Iteration   2: 7.076 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 8.112 ops/ms
Iteration   2: 8.436 ops/ms
Iteration   3: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.309 ±(99.9%) 3.159 ops/ms [Average]
  (min, avg, max) = (8.112, 8.309, 8.436), stdev = 0.173
  CI (99.9%): [5.150, 11.468] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.347 ops/ms
# Warmup Iteration   2: 6.968 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 7.979 ops/ms
Iteration   2: 8.068 ops/ms
Iteration   3: 8.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.093 ±(99.9%) 2.361 ops/ms [Average]
  (min, avg, max) = (7.979, 8.093, 8.234), stdev = 0.129
  CI (99.9%): [5.732, 10.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.348 ops/ms
# Warmup Iteration   2: 6.106 ops/ms
# Warmup Iteration   3: 6.768 ops/ms
Iteration   1: 6.782 ops/ms
Iteration   2: 6.990 ops/ms
Iteration   3: 6.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.889 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (6.782, 6.889, 6.990), stdev = 0.104
  CI (99.9%): [4.984, 8.793] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.778 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.002 ms/op
Iteration   1: 3.832 ±(99.9%) 0.005 ms/op
Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
Iteration   3: 3.841 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.882 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.832, 3.882, 3.973), stdev = 0.079
  CI (99.9%): [2.440, 5.324] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.504 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.004 ms/op
Iteration   1: 3.663 ±(99.9%) 0.004 ms/op
Iteration   2: 3.828 ±(99.9%) 0.004 ms/op
Iteration   3: 3.854 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.782 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (3.663, 3.782, 3.854), stdev = 0.104
  CI (99.9%): [1.890, 5.673] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.990 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.671 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.830 ±(99.9%) 0.003 ms/op
Iteration   1: 4.022 ±(99.9%) 0.002 ms/op
Iteration   2: 4.199 ±(99.9%) 0.005 ms/op
Iteration   3: 4.037 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.086 ±(99.9%) 1.785 ms/op [Average]
  (min, avg, max) = (4.022, 4.086, 4.199), stdev = 0.098
  CI (99.9%): [2.301, 5.871] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.766 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.008 ms/op
Iteration   1: 4.695 ±(99.9%) 0.010 ms/op
Iteration   2: 4.613 ±(99.9%) 0.006 ms/op
Iteration   3: 4.490 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.599 ±(99.9%) 1.884 ms/op [Average]
  (min, avg, max) = (4.490, 4.599, 4.695), stdev = 0.103
  CI (99.9%): [2.716, 6.483] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.355 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 4.867 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.017 ms/op
Iteration   1: 4.035 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.758 ms/op
                 createUser·p0.999:  18.678 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.915 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  25.004 ms/op
                 createUser·p0.9999: 29.158 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 4.020 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.341 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  15.580 ms/op
                 createUser·p0.9999: 30.802 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240521
  mean =      3.989 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 628 
    [ 2.500,  5.000) = 226138 
    [ 5.000,  7.500) = 11794 
    [ 7.500, 10.000) = 1238 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.341 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     18.558 ms/op
     p(99.9900) =     29.422 ms/op
     p(99.9990) =     31.278 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.369 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.010 ms/op
Iteration   1: 3.788 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.668 ms/op
                 existUser·p0.999:  22.692 ms/op
                 existUser·p0.9999: 25.510 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 3.720 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.765 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.039 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  14.828 ms/op
                 existUser·p0.9999: 26.719 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.357 ms/op
                 existUser·p0.999:  25.507 ms/op
                 existUser·p0.9999: 28.606 ms/op
                 existUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255065
  mean =      3.763 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 761 
    [ 2.500,  5.000) = 246795 
    [ 5.000,  7.500) = 5751 
    [ 7.500, 10.000) = 790 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 124 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     21.524 ms/op
     p(99.9900) =     27.935 ms/op
     p(99.9990) =     29.008 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.391 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.408 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.149 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   8.077 ms/op
                 getUser·p0.999:  22.552 ms/op
                 getUser·p0.9999: 28.247 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.856 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  24.381 ms/op
                 getUser·p0.9999: 27.132 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 3.998 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.319 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  15.078 ms/op
                 getUser·p0.9999: 29.655 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242535
  mean =      3.957 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 379 
    [ 2.500,  5.000) = 230045 
    [ 5.000,  7.500) = 9857 
    [ 7.500, 10.000) = 1435 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.319 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     22.461 ms/op
     p(99.9900) =     28.533 ms/op
     p(99.9990) =     30.105 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.321 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.389 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.773 ±(99.9%) 0.015 ms/op
Iteration   1: 4.885 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   9.528 ms/op
                 listUser·p0.999:  23.039 ms/op
                 listUser·p0.9999: 24.567 ms/op
                 listUser·p1.00:   26.247 ms/op

Iteration   2: 4.828 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.480 ms/op
                 listUser·p0.95:   6.035 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 21.476 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 4.687 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   7.608 ms/op
                 listUser·p0.999:  15.974 ms/op
                 listUser·p0.9999: 18.308 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199857
  mean =      4.799 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 150469 
    [ 5.000,  7.500) = 45291 
    [ 7.500, 10.000) = 2892 
    [10.000, 12.500) = 585 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.942 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     23.954 ms/op
     p(99.9990) =     25.462 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.039 ± 4.099  ops/ms
ClientPb.existUser                       thrpt       3   8.309 ± 3.159  ops/ms
ClientPb.getUser                         thrpt       3   8.093 ± 2.361  ops/ms
ClientPb.listUser                        thrpt       3   6.889 ± 1.904  ops/ms
ClientPb.createUser                       avgt       3   3.882 ± 1.442   ms/op
ClientPb.existUser                        avgt       3   3.782 ± 1.891   ms/op
ClientPb.getUser                          avgt       3   4.086 ± 1.785   ms/op
ClientPb.listUser                         avgt       3   4.599 ± 1.884   ms/op
ClientPb.createUser                     sample  240521   3.989 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.266           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.558           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.422           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  255065   3.763 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.537           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.524           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.935           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.360           ms/op
ClientPb.getUser                        sample  242535   3.957 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.319           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.461           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  199857   4.799 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.942           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.431           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.954           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.247           ms/op
