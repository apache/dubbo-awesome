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
# Warmup Iteration   1: 1.584 ops/ms
# Warmup Iteration   2: 3.544 ops/ms
# Warmup Iteration   3: 7.301 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.973 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.933 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (7.777, 7.933, 8.048), stdev = 0.140
  CI (99.9%): [5.374, 10.491] (assumes normal distribution)


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
# Warmup Iteration   1: 2.398 ops/ms
# Warmup Iteration   2: 7.147 ops/ms
# Warmup Iteration   3: 7.932 ops/ms
Iteration   1: 8.143 ops/ms
Iteration   2: 8.345 ops/ms
Iteration   3: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.226 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (8.143, 8.226, 8.345), stdev = 0.106
  CI (99.9%): [6.297, 10.156] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 6.935 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 7.935 ops/ms
Iteration   2: 7.971 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.035 ±(99.9%) 2.616 ops/ms [Average]
  (min, avg, max) = (7.935, 8.035, 8.200), stdev = 0.143
  CI (99.9%): [5.420, 10.651] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 5.852 ops/ms
# Warmup Iteration   3: 6.469 ops/ms
Iteration   1: 6.677 ops/ms
Iteration   2: 6.646 ops/ms
Iteration   3: 6.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.693 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (6.646, 6.693, 6.757), stdev = 0.057
  CI (99.9%): [5.652, 7.735] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.329 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 4.494 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.296 ±(99.9%) 0.004 ms/op
Iteration   1: 4.060 ±(99.9%) 0.006 ms/op
Iteration   2: 4.035 ±(99.9%) 0.005 ms/op
Iteration   3: 4.023 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.039 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (4.023, 4.039, 4.060), stdev = 0.019
  CI (99.9%): [3.700, 4.378] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.311 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.677 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.008 ms/op
Iteration   1: 3.924 ±(99.9%) 0.004 ms/op
Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
Iteration   3: 3.813 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.830 ±(99.9%) 1.569 ms/op [Average]
  (min, avg, max) = (3.754, 3.830, 3.924), stdev = 0.086
  CI (99.9%): [2.261, 5.399] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.624 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.003 ms/op
Iteration   1: 4.095 ±(99.9%) 0.004 ms/op
Iteration   2: 3.985 ±(99.9%) 0.004 ms/op
Iteration   3: 3.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.020 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (3.978, 4.020, 4.095), stdev = 0.066
  CI (99.9%): [2.822, 5.218] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.019 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.790 ±(99.9%) 0.007 ms/op
Iteration   1: 4.679 ±(99.9%) 0.008 ms/op
Iteration   2: 4.763 ±(99.9%) 0.009 ms/op
Iteration   3: 4.742 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.728 ±(99.9%) 0.804 ms/op [Average]
  (min, avg, max) = (4.679, 4.728, 4.763), stdev = 0.044
  CI (99.9%): [3.924, 5.532] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.741 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.498 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.019 ms/op
Iteration   1: 4.157 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   4.035 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  23.755 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   27.165 ms/op

Iteration   2: 3.958 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  12.943 ms/op
                 createUser·p0.9999: 26.048 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 4.008 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   7.365 ms/op
                 createUser·p0.999:  30.253 ms/op
                 createUser·p0.9999: 43.780 ms/op
                 createUser·p1.00:   52.363 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237635
  mean =      4.039 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 226729 
    [ 5.000, 10.000) = 10228 
    [10.000, 15.000) = 302 
    [15.000, 20.000) = 39 
    [20.000, 25.000) = 125 
    [25.000, 30.000) = 128 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     37.105 ms/op
     p(99.9990) =     50.736 ms/op
     p(99.9999) =     52.363 ms/op
    p(100.0000) =     52.363 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.846 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.894 ±(99.9%) 0.011 ms/op
Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  22.839 ms/op
                 existUser·p0.9999: 25.679 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   2: 4.025 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.332 ms/op
                 existUser·p0.999:  15.155 ms/op
                 existUser·p0.9999: 28.870 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   3: 3.947 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.737 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  19.038 ms/op
                 existUser·p0.9999: 30.136 ms/op
                 existUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242186
  mean =      3.964 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 287 
    [ 2.500,  5.000) = 231157 
    [ 5.000,  7.500) = 7933 
    [ 7.500, 10.000) = 2006 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     29.550 ms/op
     p(99.9990) =     30.466 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 13.698 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.057 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.011 ms/op
Iteration   1: 4.107 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  22.970 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.830 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  9.871 ms/op
                 getUser·p0.9999: 28.038 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 4.178 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  26.416 ms/op
                 getUser·p0.9999: 34.015 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236235
  mean =      4.063 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 224519 
    [ 5.000,  7.500) = 9017 
    [ 7.500, 10.000) = 1663 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     22.995 ms/op
     p(99.9900) =     31.896 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 16.094 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.500 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.987 ±(99.9%) 0.015 ms/op
Iteration   1: 4.966 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   10.502 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 4.794 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  18.491 ms/op
                 listUser·p0.9999: 21.878 ms/op
                 listUser·p1.00:   22.970 ms/op

Iteration   3: 4.761 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  15.782 ms/op
                 listUser·p0.9999: 17.999 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198199
  mean =      4.839 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 153524 
    [ 5.000,  7.500) = 40322 
    [ 7.500, 10.000) = 2848 
    [10.000, 12.500) = 804 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 233 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     17.786 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.745 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.933 ± 2.559  ops/ms
ClientPb.existUser                       thrpt       3   8.226 ± 1.929  ops/ms
ClientPb.getUser                         thrpt       3   8.035 ± 2.616  ops/ms
ClientPb.listUser                        thrpt       3   6.693 ± 1.042  ops/ms
ClientPb.createUser                       avgt       3   4.039 ± 0.339   ms/op
ClientPb.existUser                        avgt       3   3.830 ± 1.569   ms/op
ClientPb.getUser                          avgt       3   4.020 ± 1.198   ms/op
ClientPb.listUser                         avgt       3   4.728 ± 0.804   ms/op
ClientPb.createUser                     sample  237635   4.039 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.576           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.105           ms/op
ClientPb.createUser:createUser·p1.00    sample          52.363           ms/op
ClientPb.existUser                      sample  242186   3.964 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.497           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.717           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.038           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.550           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.573           ms/op
ClientPb.getUser                        sample  236235   4.063 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.691           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.989           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.782           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.995           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.896           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  198199   4.839 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.786           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.970           ms/op
