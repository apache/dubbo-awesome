# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.011 ops/ms
# Warmup Iteration   2: 4.836 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 9.049 ops/ms
Iteration   2: 9.000 ops/ms
Iteration   3: 9.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.102 ±(99.9%) 2.491 ops/ms [Average]
  (min, avg, max) = (9.000, 9.102, 9.257), stdev = 0.137
  CI (99.9%): [6.611, 11.593] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.480 ops/ms
# Warmup Iteration   2: 8.575 ops/ms
# Warmup Iteration   3: 9.887 ops/ms
Iteration   1: 9.648 ops/ms
Iteration   2: 10.008 ops/ms
Iteration   3: 9.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.837 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (9.648, 9.837, 10.008), stdev = 0.181
  CI (99.9%): [6.541, 13.134] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.670 ops/ms
# Warmup Iteration   2: 8.466 ops/ms
# Warmup Iteration   3: 9.134 ops/ms
Iteration   1: 9.098 ops/ms
Iteration   2: 9.214 ops/ms
Iteration   3: 9.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.187 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (9.098, 9.187, 9.249), stdev = 0.079
  CI (99.9%): [7.749, 10.625] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.623 ops/ms
# Warmup Iteration   2: 6.600 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.821 ops/ms
Iteration   2: 7.966 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.860 ±(99.9%) 1.689 ops/ms [Average]
  (min, avg, max) = (7.793, 7.860, 7.966), stdev = 0.093
  CI (99.9%): [6.171, 9.549] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.964 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.011 ms/op
Iteration   1: 3.342 ±(99.9%) 0.012 ms/op
Iteration   2: 3.265 ±(99.9%) 0.010 ms/op
Iteration   3: 3.426 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.345 ±(99.9%) 1.466 ms/op [Average]
  (min, avg, max) = (3.265, 3.345, 3.426), stdev = 0.080
  CI (99.9%): [1.878, 4.811] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.563 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.006 ms/op
Iteration   1: 3.264 ±(99.9%) 0.004 ms/op
Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
Iteration   3: 3.211 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.220 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.184, 3.220, 3.264), stdev = 0.041
  CI (99.9%): [2.477, 3.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.891 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.006 ms/op
Iteration   1: 3.468 ±(99.9%) 0.007 ms/op
Iteration   2: 3.505 ±(99.9%) 0.009 ms/op
Iteration   3: 3.334 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.436 ±(99.9%) 1.639 ms/op [Average]
  (min, avg, max) = (3.334, 3.436, 3.505), stdev = 0.090
  CI (99.9%): [1.797, 5.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.368 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.009 ms/op
Iteration   1: 3.889 ±(99.9%) 0.014 ms/op
Iteration   2: 3.968 ±(99.9%) 0.010 ms/op
Iteration   3: 3.851 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.903 ±(99.9%) 1.092 ms/op [Average]
  (min, avg, max) = (3.851, 3.903, 3.968), stdev = 0.060
  CI (99.9%): [2.811, 4.995] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.906 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  19.603 ms/op
                 createUser·p0.9999: 23.106 ms/op
                 createUser·p1.00:   24.150 ms/op

Iteration   2: 3.313 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  19.611 ms/op
                 createUser·p0.9999: 24.817 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 3.421 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.829 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 28.071 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283647
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3853 
    [ 2.500,  5.000) = 272594 
    [ 5.000,  7.500) = 6130 
    [ 7.500, 10.000) = 610 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     26.467 ms/op
     p(99.9990) =     28.743 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.367 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
Iteration   1: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.303 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  9.830 ms/op
                 existUser·p0.9999: 27.079 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 3.425 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.743 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  20.890 ms/op
                 existUser·p0.9999: 24.619 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  16.433 ms/op
                 existUser·p0.9999: 24.805 ms/op
                 existUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292800
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14623 
    [ 2.500,  5.000) = 272522 
    [ 5.000,  7.500) = 4695 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     25.910 ms/op
     p(99.9990) =     28.939 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.278 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.011 ms/op
Iteration   1: 3.361 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  20.299 ms/op
                 getUser·p0.9999: 23.132 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.400 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  21.952 ms/op
                 getUser·p0.9999: 24.798 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   3: 3.453 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  18.163 ms/op
                 getUser·p0.9999: 25.682 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281899
  mean =      3.404 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10024 
    [ 2.500,  5.000) = 264654 
    [ 5.000,  7.500) = 5873 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     18.321 ms/op
     p(99.9900) =     24.799 ms/op
     p(99.9990) =     26.745 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.383 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.013 ms/op
Iteration   1: 4.002 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  19.234 ms/op
                 listUser·p0.9999: 23.986 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 3.843 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.625 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  16.996 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 3.997 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.541 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 15.761 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243280
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 235005 
    [ 5.000,  7.500) = 5933 
    [ 7.500, 10.000) = 1456 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     22.763 ms/op
     p(99.9990) =     24.627 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.102 ± 2.491  ops/ms
ClientPb.existUser                       thrpt       3   9.837 ± 3.297  ops/ms
ClientPb.getUser                         thrpt       3   9.187 ± 1.438  ops/ms
ClientPb.listUser                        thrpt       3   7.860 ± 1.689  ops/ms
ClientPb.createUser                       avgt       3   3.345 ± 1.466   ms/op
ClientPb.existUser                        avgt       3   3.220 ± 0.743   ms/op
ClientPb.getUser                          avgt       3   3.436 ± 1.639   ms/op
ClientPb.listUser                         avgt       3   3.903 ± 1.092   ms/op
ClientPb.createUser                     sample  283647   3.383 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.104           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.467           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.131           ms/op
ClientPb.existUser                      sample  292800   3.279 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.303           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.018           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.417           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.910           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  281899   3.404 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.524           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.321           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.799           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  243280   3.946 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.625           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.763           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
