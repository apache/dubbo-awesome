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
# Warmup Iteration   1: 2.520 ops/ms
# Warmup Iteration   2: 6.370 ops/ms
# Warmup Iteration   3: 9.120 ops/ms
Iteration   1: 9.931 ops/ms
Iteration   2: 10.176 ops/ms
Iteration   3: 10.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.203 ±(99.9%) 5.230 ops/ms [Average]
  (min, avg, max) = (9.931, 10.203, 10.502), stdev = 0.287
  CI (99.9%): [4.973, 15.432] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 9.722 ops/ms
# Warmup Iteration   3: 9.785 ops/ms
Iteration   1: 10.804 ops/ms
Iteration   2: 10.725 ops/ms
Iteration   3: 10.770 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.766 ±(99.9%) 0.725 ops/ms [Average]
  (min, avg, max) = (10.725, 10.766, 10.804), stdev = 0.040
  CI (99.9%): [10.041, 11.491] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ops/ms
# Warmup Iteration   2: 9.352 ops/ms
# Warmup Iteration   3: 9.389 ops/ms
Iteration   1: 10.412 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.372 ±(99.9%) 4.433 ops/ms [Average]
  (min, avg, max) = (10.111, 10.372, 10.592), stdev = 0.243
  CI (99.9%): [5.939, 14.805] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ops/ms
# Warmup Iteration   2: 7.931 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.534 ops/ms
Iteration   2: 8.385 ops/ms
Iteration   3: 8.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.509 ±(99.9%) 2.084 ops/ms [Average]
  (min, avg, max) = (8.385, 8.509, 8.610), stdev = 0.114
  CI (99.9%): [6.425, 10.594] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.922 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.004 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
Iteration   2: 3.180 ±(99.9%) 0.005 ms/op
Iteration   3: 3.220 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.166 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.099, 3.166, 3.220), stdev = 0.062
  CI (99.9%): [2.036, 4.297] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.171 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.007 ms/op
Iteration   3: 3.086 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.111 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.086, 3.111, 3.158), stdev = 0.041
  CI (99.9%): [2.356, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 7.316 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.509 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.080 ±(99.9%) 0.002 ms/op
Iteration   2: 3.231 ±(99.9%) 0.004 ms/op
Iteration   3: 3.095 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.135 ±(99.9%) 1.524 ms/op [Average]
  (min, avg, max) = (3.080, 3.135, 3.231), stdev = 0.084
  CI (99.9%): [1.611, 4.660] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.689 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.011 ms/op
Iteration   1: 3.698 ±(99.9%) 0.010 ms/op
Iteration   2: 3.733 ±(99.9%) 0.003 ms/op
Iteration   3: 3.782 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.738 ±(99.9%) 0.768 ms/op [Average]
  (min, avg, max) = (3.698, 3.738, 3.782), stdev = 0.042
  CI (99.9%): [2.970, 4.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.393 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.010 ms/op
Iteration   1: 3.131 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  21.326 ms/op
                 createUser·p0.9999: 29.295 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 26.115 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   3: 3.229 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.266 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  17.037 ms/op
                 createUser·p0.9999: 30.736 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301688
  mean =      3.181 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10335 
    [ 2.500,  5.000) = 285800 
    [ 5.000,  7.500) = 4443 
    [ 7.500, 10.000) = 548 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     18.268 ms/op
     p(99.9900) =     29.715 ms/op
     p(99.9990) =     31.096 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 6.651 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
Iteration   1: 2.988 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.109 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  11.355 ms/op
                 existUser·p0.9999: 18.620 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  9.660 ms/op
                 existUser·p0.9999: 21.672 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  8.454 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314048
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29354 
    [ 2.500,  5.000) = 280372 
    [ 5.000,  7.500) = 3639 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.248 ms/op
     p(95.0000) =      3.539 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     11.075 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     22.137 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 7.764 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.492 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.011 ms/op
Iteration   1: 3.172 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  10.061 ms/op
                 getUser·p0.9999: 20.901 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  11.356 ms/op
                 getUser·p0.9999: 23.141 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.189 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  11.600 ms/op
                 getUser·p0.9999: 44.696 ms/op
                 getUser·p1.00:   45.548 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299064
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 290966 
    [ 5.000, 10.000) = 7705 
    [10.000, 15.000) = 109 
    [15.000, 20.000) = 82 
    [20.000, 25.000) = 137 
    [25.000, 30.000) = 33 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     43.778 ms/op
     p(99.9990) =     45.483 ms/op
     p(99.9999) =     45.548 ms/op
    p(100.0000) =     45.548 ms/op


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
# Warmup Iteration   1: 9.162 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.012 ms/op
Iteration   1: 3.689 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 19.606 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   2: 3.617 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 15.581 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 3.603 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.703 ms/op
                 listUser·p0.95:   4.100 ms/op
                 listUser·p0.99:   6.005 ms/op
                 listUser·p0.999:  13.947 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 263766
  mean =      3.636 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 256686 
    [ 5.000,  7.500) = 5371 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.614 ms/op
     p(99.9000) =     13.844 ms/op
     p(99.9900) =     18.948 ms/op
     p(99.9990) =     19.947 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.203 ± 5.230  ops/ms
ClientPb.existUser                       thrpt       3  10.766 ± 0.725  ops/ms
ClientPb.getUser                         thrpt       3  10.372 ± 4.433  ops/ms
ClientPb.listUser                        thrpt       3   8.509 ± 2.084  ops/ms
ClientPb.createUser                       avgt       3   3.166 ± 1.131   ms/op
ClientPb.existUser                        avgt       3   3.111 ± 0.755   ms/op
ClientPb.getUser                          avgt       3   3.135 ± 1.524   ms/op
ClientPb.listUser                         avgt       3   3.738 ± 0.768   ms/op
ClientPb.createUser                     sample  301688   3.181 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.266           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.715           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.392           ms/op
ClientPb.existUser                      sample  314048   3.055 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.513           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.282           ms/op
ClientPb.getUser                        sample  299064   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.583           ms/op
ClientPb.getUser:getUser·p0.9999        sample          43.778           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.548           ms/op
ClientPb.listUser                       sample  263766   3.636 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.539           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.614           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.844           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.948           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.087           ms/op
