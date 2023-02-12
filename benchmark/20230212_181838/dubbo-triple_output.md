# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.392 ops/ms
# Warmup Iteration   2: 3.251 ops/ms
# Warmup Iteration   3: 6.132 ops/ms
Iteration   1: 6.476 ops/ms
Iteration   2: 6.784 ops/ms
Iteration   3: 6.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.731 ±(99.9%) 4.262 ops/ms [Average]
  (min, avg, max) = (6.476, 6.731, 6.934), stdev = 0.234
  CI (99.9%): [2.470, 10.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 5.889 ops/ms
# Warmup Iteration   3: 7.027 ops/ms
Iteration   1: 7.082 ops/ms
Iteration   2: 6.992 ops/ms
Iteration   3: 7.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.103 ±(99.9%) 2.226 ops/ms [Average]
  (min, avg, max) = (6.992, 7.103, 7.234), stdev = 0.122
  CI (99.9%): [4.877, 9.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 6.206 ops/ms
# Warmup Iteration   3: 6.654 ops/ms
Iteration   1: 6.649 ops/ms
Iteration   2: 6.871 ops/ms
Iteration   3: 6.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.769 ±(99.9%) 2.040 ops/ms [Average]
  (min, avg, max) = (6.649, 6.769, 6.871), stdev = 0.112
  CI (99.9%): [4.729, 8.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 4.795 ops/ms
# Warmup Iteration   3: 5.650 ops/ms
Iteration   1: 5.920 ops/ms
Iteration   2: 5.889 ops/ms
Iteration   3: 5.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.835 ±(99.9%) 2.232 ops/ms [Average]
  (min, avg, max) = (5.694, 5.835, 5.920), stdev = 0.122
  CI (99.9%): [3.603, 8.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 14.567 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.104 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.014 ms/op
Iteration   1: 4.753 ±(99.9%) 0.007 ms/op
Iteration   2: 4.595 ±(99.9%) 0.011 ms/op
Iteration   3: 4.747 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.698 ±(99.9%) 1.636 ms/op [Average]
  (min, avg, max) = (4.595, 4.698, 4.753), stdev = 0.090
  CI (99.9%): [3.062, 6.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.113 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.957 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.401 ±(99.9%) 0.012 ms/op
Iteration   1: 4.319 ±(99.9%) 0.012 ms/op
Iteration   2: 4.412 ±(99.9%) 0.010 ms/op
Iteration   3: 4.235 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.322 ±(99.9%) 1.609 ms/op [Average]
  (min, avg, max) = (4.235, 4.322, 4.412), stdev = 0.088
  CI (99.9%): [2.713, 5.931] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.401 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.327 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.845 ±(99.9%) 0.011 ms/op
Iteration   1: 4.687 ±(99.9%) 0.014 ms/op
Iteration   2: 4.628 ±(99.9%) 0.010 ms/op
Iteration   3: 4.761 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.692 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (4.628, 4.692, 4.761), stdev = 0.067
  CI (99.9%): [3.476, 5.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.697 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.071 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.019 ms/op
Iteration   1: 5.244 ±(99.9%) 0.018 ms/op
Iteration   2: 5.307 ±(99.9%) 0.015 ms/op
Iteration   3: 5.311 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.288 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (5.244, 5.288, 5.311), stdev = 0.038
  CI (99.9%): [4.599, 5.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.129 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 5.659 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.091 ±(99.9%) 0.019 ms/op
Iteration   1: 4.738 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.357 ms/op
                 createUser·p0.99:   8.667 ms/op
                 createUser·p0.999:  19.185 ms/op
                 createUser·p0.9999: 32.218 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   2: 4.974 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   4.719 ms/op
                 createUser·p0.90:   6.070 ms/op
                 createUser·p0.95:   6.824 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  21.332 ms/op
                 createUser·p0.9999: 29.879 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   3: 4.796 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.048 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.816 ms/op
                 createUser·p0.95:   6.332 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  19.983 ms/op
                 createUser·p0.9999: 29.448 ms/op
                 createUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 198471
  mean =      4.834 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 138588 
    [ 5.000,  7.500) = 54243 
    [ 7.500, 10.000) = 4101 
    [10.000, 12.500) = 833 
    [12.500, 15.000) = 276 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.048 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     21.268 ms/op
     p(99.9900) =     31.036 ms/op
     p(99.9990) =     33.263 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.689 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 4.877 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.519 ±(99.9%) 0.014 ms/op
Iteration   1: 4.583 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.974 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.218 ms/op
                 existUser·p0.99:   8.372 ms/op
                 existUser·p0.999:  14.634 ms/op
                 existUser·p0.9999: 30.679 ms/op
                 existUser·p1.00:   31.687 ms/op

Iteration   2: 4.721 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   6.398 ms/op
                 existUser·p0.99:   7.889 ms/op
                 existUser·p0.999:  14.638 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   3: 4.567 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.146 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.390 ms/op
                 existUser·p0.95:   6.177 ms/op
                 existUser·p0.99:   9.290 ms/op
                 existUser·p0.999:  19.063 ms/op
                 existUser·p0.9999: 34.471 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 207737
  mean =      4.622 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 158432 
    [ 5.000,  7.500) = 45677 
    [ 7.500, 10.000) = 2516 
    [10.000, 12.500) = 559 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     18.367 ms/op
     p(99.9900) =     33.700 ms/op
     p(99.9990) =     35.314 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.384 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.499 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.913 ±(99.9%) 0.016 ms/op
Iteration   1: 4.812 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.726 ms/op
                 getUser·p0.95:   7.004 ms/op
                 getUser·p0.99:   9.568 ms/op
                 getUser·p0.999:  17.694 ms/op
                 getUser·p0.9999: 25.857 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 4.991 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.363 ms/op
                 getUser·p0.50:   4.653 ms/op
                 getUser·p0.90:   6.447 ms/op
                 getUser·p0.95:   7.315 ms/op
                 getUser·p0.99:   9.880 ms/op
                 getUser·p0.999:  23.269 ms/op
                 getUser·p0.9999: 28.804 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 4.650 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.665 ms/op
                 getUser·p0.999:  13.850 ms/op
                 getUser·p0.9999: 34.021 ms/op
                 getUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 199221
  mean =      4.814 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 147155 
    [ 5.000,  7.500) = 45889 
    [ 7.500, 10.000) = 4811 
    [10.000, 12.500) = 947 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.808 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     17.615 ms/op
     p(99.9900) =     33.177 ms/op
     p(99.9990) =     34.965 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.938 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 6.761 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.048 ±(99.9%) 0.024 ms/op
Iteration   1: 5.560 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.603 ms/op
                 listUser·p0.99:   11.269 ms/op
                 listUser·p0.999:  24.395 ms/op
                 listUser·p0.9999: 30.081 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   2: 5.696 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.250 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  22.704 ms/op
                 listUser·p0.9999: 27.702 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   3: 5.750 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  18.884 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 169309
  mean =      5.668 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 40151 
    [ 5.000,  7.500) = 120020 
    [ 7.500, 10.000) = 6899 
    [10.000, 12.500) = 1352 
    [12.500, 15.000) = 361 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.779 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     28.117 ms/op
     p(99.9990) =     32.362 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.731 ± 4.262  ops/ms
ClientPb.existUser                       thrpt       3   7.103 ± 2.226  ops/ms
ClientPb.getUser                         thrpt       3   6.769 ± 2.040  ops/ms
ClientPb.listUser                        thrpt       3   5.835 ± 2.232  ops/ms
ClientPb.createUser                       avgt       3   4.698 ± 1.636   ms/op
ClientPb.existUser                        avgt       3   4.322 ± 1.609   ms/op
ClientPb.getUser                          avgt       3   4.692 ± 1.216   ms/op
ClientPb.listUser                         avgt       3   5.288 ± 0.688   ms/op
ClientPb.createUser                     sample  198471   4.834 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.048           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.513           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.306           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.036           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  207737   4.622 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.341           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.372           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.367           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.700           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  199221   4.814 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.575           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.571           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.208           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.615           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.177           ms/op
ClientPb.getUser:getUser·p1.00          sample          39.322           ms/op
ClientPb.listUser                       sample  169309   5.668 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.327           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.676           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.779           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.315           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.408           ms/op
