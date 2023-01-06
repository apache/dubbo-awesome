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
# Warmup Iteration   1: 1.710 ops/ms
# Warmup Iteration   2: 4.346 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 8.233 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.154 ±(99.9%) 2.852 ops/ms [Average]
  (min, avg, max) = (7.974, 8.154, 8.255), stdev = 0.156
  CI (99.9%): [5.301, 11.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 6.880 ops/ms
# Warmup Iteration   3: 8.459 ops/ms
Iteration   1: 8.018 ops/ms
Iteration   2: 8.788 ops/ms
Iteration   3: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.433 ±(99.9%) 7.085 ops/ms [Average]
  (min, avg, max) = (8.018, 8.433, 8.788), stdev = 0.388
  CI (99.9%): [1.348, 15.518] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.376 ops/ms
# Warmup Iteration   2: 7.112 ops/ms
# Warmup Iteration   3: 8.308 ops/ms
Iteration   1: 8.240 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.355 ±(99.9%) 2.685 ops/ms [Average]
  (min, avg, max) = (8.240, 8.355, 8.521), stdev = 0.147
  CI (99.9%): [5.669, 11.040] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.289 ops/ms
# Warmup Iteration   2: 5.998 ops/ms
# Warmup Iteration   3: 6.788 ops/ms
Iteration   1: 7.186 ops/ms
Iteration   2: 7.077 ops/ms
Iteration   3: 6.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.080 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (6.978, 7.080, 7.186), stdev = 0.104
  CI (99.9%): [5.181, 8.979] (assumes normal distribution)


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
# Warmup Iteration   1: 13.006 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.006 ms/op
Iteration   1: 4.268 ±(99.9%) 0.008 ms/op
Iteration   2: 3.828 ±(99.9%) 0.014 ms/op
Iteration   3: 3.814 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.970 ±(99.9%) 4.713 ms/op [Average]
  (min, avg, max) = (3.814, 3.970, 4.268), stdev = 0.258
  CI (99.9%): [≈ 0, 8.683] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.662 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.008 ms/op
Iteration   1: 3.875 ±(99.9%) 0.003 ms/op
Iteration   2: 3.807 ±(99.9%) 0.009 ms/op
Iteration   3: 3.566 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.750 ±(99.9%) 2.960 ms/op [Average]
  (min, avg, max) = (3.566, 3.750, 3.875), stdev = 0.162
  CI (99.9%): [0.790, 6.709] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 12.482 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.313 ±(99.9%) 0.007 ms/op
Iteration   1: 4.134 ±(99.9%) 0.010 ms/op
Iteration   2: 4.067 ±(99.9%) 0.008 ms/op
Iteration   3: 4.080 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.094 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (4.067, 4.094, 4.134), stdev = 0.035
  CI (99.9%): [3.450, 4.737] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 14.554 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.765 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.010 ms/op
Iteration   1: 4.368 ±(99.9%) 0.016 ms/op
Iteration   2: 4.565 ±(99.9%) 0.019 ms/op
Iteration   3: 4.702 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.545 ±(99.9%) 3.061 ms/op [Average]
  (min, avg, max) = (4.368, 4.545, 4.702), stdev = 0.168
  CI (99.9%): [1.484, 7.607] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.866 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.547 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.014 ms/op
Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  11.318 ms/op
                 createUser·p0.9999: 25.706 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 3.913 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  21.660 ms/op
                 createUser·p0.9999: 29.991 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 3.919 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  24.660 ms/op
                 createUser·p0.9999: 33.063 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248685
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 804 
    [ 2.500,  5.000) = 238226 
    [ 5.000,  7.500) = 8267 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     20.501 ms/op
     p(99.9900) =     31.920 ms/op
     p(99.9990) =     33.375 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.888 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
Iteration   1: 3.789 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  22.089 ms/op
                 existUser·p0.9999: 25.006 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.833 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 32.352 ms/op
                 existUser·p1.00:   33.358 ms/op

Iteration   3: 3.716 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.694 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  9.531 ms/op
                 existUser·p0.9999: 41.731 ms/op
                 existUser·p1.00:   43.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254031
  mean =      3.779 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244057 
    [ 5.000, 10.000) = 9545 
    [10.000, 15.000) = 173 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 88 
    [25.000, 30.000) = 53 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     16.488 ms/op
     p(99.9900) =     40.475 ms/op
     p(99.9990) =     43.022 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


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
# Warmup Iteration   1: 12.639 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.145 ±(99.9%) 0.017 ms/op
Iteration   1: 3.769 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   7.156 ms/op
                 getUser·p0.999:  22.249 ms/op
                 getUser·p0.9999: 33.817 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   2: 3.833 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.814 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  23.855 ms/op
                 getUser·p0.9999: 30.184 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   3: 3.764 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  26.081 ms/op
                 getUser·p0.9999: 34.308 ms/op
                 getUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 253433
  mean =      3.788 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1475 
    [ 2.500,  5.000) = 244680 
    [ 5.000,  7.500) = 5714 
    [ 7.500, 10.000) = 1038 
    [10.000, 12.500) = 177 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     23.120 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     35.354 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 13.800 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.128 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.016 ms/op
Iteration   1: 4.337 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  24.922 ms/op
                 listUser·p0.9999: 30.205 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 4.550 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  17.836 ms/op
                 listUser·p0.9999: 24.572 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   3: 4.729 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.675 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   9.241 ms/op
                 listUser·p0.999:  17.085 ms/op
                 listUser·p0.9999: 20.856 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211647
  mean =      4.533 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 186798 
    [ 5.000,  7.500) = 20192 
    [ 7.500, 10.000) = 3445 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     28.202 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.154 ± 2.852  ops/ms
ClientPb.existUser                       thrpt       3   8.433 ± 7.085  ops/ms
ClientPb.getUser                         thrpt       3   8.355 ± 2.685  ops/ms
ClientPb.listUser                        thrpt       3   7.080 ± 1.899  ops/ms
ClientPb.createUser                       avgt       3   3.970 ± 4.713   ms/op
ClientPb.existUser                        avgt       3   3.750 ± 2.960   ms/op
ClientPb.getUser                          avgt       3   4.094 ± 0.643   ms/op
ClientPb.listUser                         avgt       3   4.545 ± 3.061   ms/op
ClientPb.createUser                     sample  248685   3.860 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.409           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.501           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.920           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391           ms/op
ClientPb.existUser                      sample  254031   3.779 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.196           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.488           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.475           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.385           ms/op
ClientPb.getUser                        sample  253433   3.788 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.386           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.120           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.554           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  211647   4.533 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.416           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.202           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
