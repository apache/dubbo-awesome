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
# Warmup Iteration   1: 1.039 ops/ms
# Warmup Iteration   2: 2.845 ops/ms
# Warmup Iteration   3: 5.919 ops/ms
Iteration   1: 6.180 ops/ms
Iteration   2: 6.498 ops/ms
Iteration   3: 6.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.386 ±(99.9%) 3.262 ops/ms [Average]
  (min, avg, max) = (6.180, 6.386, 6.498), stdev = 0.179
  CI (99.9%): [3.124, 9.647] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.910 ops/ms
# Warmup Iteration   2: 5.585 ops/ms
# Warmup Iteration   3: 6.372 ops/ms
Iteration   1: 6.546 ops/ms
Iteration   2: 6.646 ops/ms
Iteration   3: 6.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.570 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (6.517, 6.570, 6.646), stdev = 0.068
  CI (99.9%): [5.331, 7.808] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.980 ops/ms
# Warmup Iteration   2: 5.354 ops/ms
# Warmup Iteration   3: 6.073 ops/ms
Iteration   1: 6.282 ops/ms
Iteration   2: 6.198 ops/ms
Iteration   3: 6.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.209 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (6.147, 6.209, 6.282), stdev = 0.068
  CI (99.9%): [4.970, 7.448] (assumes normal distribution)


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
# Warmup Iteration   1: 1.785 ops/ms
# Warmup Iteration   2: 4.076 ops/ms
# Warmup Iteration   3: 5.196 ops/ms
Iteration   1: 5.295 ops/ms
Iteration   2: 5.064 ops/ms
Iteration   3: 5.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.218 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (5.064, 5.218, 5.296), stdev = 0.134
  CI (99.9%): [2.781, 7.656] (assumes normal distribution)


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
# Warmup Iteration   1: 17.120 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.718 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.419 ±(99.9%) 0.011 ms/op
Iteration   1: 5.391 ±(99.9%) 0.012 ms/op
Iteration   2: 5.249 ±(99.9%) 0.010 ms/op
Iteration   3: 4.908 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.183 ±(99.9%) 4.531 ms/op [Average]
  (min, avg, max) = (4.908, 5.183, 5.391), stdev = 0.248
  CI (99.9%): [0.652, 9.713] (assumes normal distribution)


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
# Warmup Iteration   1: 14.405 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.166 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.009 ms/op
Iteration   1: 4.936 ±(99.9%) 0.013 ms/op
Iteration   2: 4.751 ±(99.9%) 0.009 ms/op
Iteration   3: 4.657 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.782 ±(99.9%) 2.587 ms/op [Average]
  (min, avg, max) = (4.657, 4.782, 4.936), stdev = 0.142
  CI (99.9%): [2.195, 7.369] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.425 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 5.785 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.405 ±(99.9%) 0.011 ms/op
Iteration   1: 5.240 ±(99.9%) 0.008 ms/op
Iteration   2: 5.116 ±(99.9%) 0.012 ms/op
Iteration   3: 5.183 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.180 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (5.116, 5.180, 5.240), stdev = 0.062
  CI (99.9%): [4.053, 6.307] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.491 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.854 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.447 ±(99.9%) 0.014 ms/op
Iteration   1: 6.335 ±(99.9%) 0.008 ms/op
Iteration   2: 6.314 ±(99.9%) 0.015 ms/op
Iteration   3: 5.672 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.107 ±(99.9%) 6.871 ms/op [Average]
  (min, avg, max) = (5.672, 6.107, 6.335), stdev = 0.377
  CI (99.9%): [≈ 0, 12.979] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.257 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 6.316 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.579 ±(99.9%) 0.021 ms/op
Iteration   1: 5.123 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.038 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.357 ms/op
                 createUser·p0.95:   7.127 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  23.727 ms/op
                 createUser·p0.9999: 27.656 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 5.250 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.175 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  24.389 ms/op
                 createUser·p0.9999: 28.669 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 5.223 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.224 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.332 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  26.903 ms/op
                 createUser·p0.9999: 30.343 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184642
  mean =      5.198 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 96993 
    [ 5.000,  7.500) = 80209 
    [ 7.500, 10.000) = 5687 
    [10.000, 12.500) = 1025 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 121 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.038 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     25.538 ms/op
     p(99.9900) =     29.725 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.712 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.008 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.036 ±(99.9%) 0.018 ms/op
Iteration   1: 4.886 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.450 ms/op
                 existUser·p0.50:   4.596 ms/op
                 existUser·p0.90:   6.119 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  22.512 ms/op
                 existUser·p0.9999: 25.505 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 4.885 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   9.535 ms/op
                 existUser·p0.999:  15.442 ms/op
                 existUser·p0.9999: 26.208 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   3: 4.937 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.204 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   6.701 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  24.430 ms/op
                 existUser·p0.9999: 32.771 ms/op
                 existUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195843
  mean =      4.903 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 135438 
    [ 5.000,  7.500) = 54620 
    [ 7.500, 10.000) = 4350 
    [10.000, 12.500) = 674 
    [12.500, 15.000) = 328 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      6.898 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     21.554 ms/op
     p(99.9900) =     30.766 ms/op
     p(99.9990) =     33.164 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.531 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.271 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.526 ±(99.9%) 0.022 ms/op
Iteration   1: 5.185 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.605 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.259 ms/op
                 getUser·p0.95:   7.135 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 30.665 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   2: 4.894 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.784 ms/op
                 getUser·p0.95:   6.406 ms/op
                 getUser·p0.99:   8.816 ms/op
                 getUser·p0.999:  18.275 ms/op
                 getUser·p0.9999: 28.668 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 5.475 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  30.428 ms/op
                 getUser·p0.9999: 39.922 ms/op
                 getUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185379
  mean =      5.174 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 98012 
    [ 5.000, 10.000) = 85962 
    [10.000, 15.000) = 1084 
    [15.000, 20.000) = 97 
    [20.000, 25.000) = 52 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     24.183 ms/op
     p(99.9900) =     37.678 ms/op
     p(99.9990) =     40.354 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.516 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.822 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.334 ±(99.9%) 0.025 ms/op
Iteration   1: 6.254 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.441 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 28.468 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   2: 6.116 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.683 ms/op
                 listUser·p0.50:   5.825 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.258 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  27.376 ms/op
                 listUser·p0.9999: 31.001 ms/op
                 listUser·p1.00:   31.850 ms/op

Iteration   3: 6.533 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.039 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  24.251 ms/op
                 listUser·p0.9999: 32.021 ms/op
                 listUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152373
  mean =      6.296 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 12658 
    [ 5.000,  7.500) = 122289 
    [ 7.500, 10.000) = 14328 
    [10.000, 12.500) = 2018 
    [12.500, 15.000) = 566 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.806 ms/op
     p(50.0000) =      6.013 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     25.907 ms/op
     p(99.9900) =     31.000 ms/op
     p(99.9990) =     32.628 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.386 ± 3.262  ops/ms
ClientPb.existUser                       thrpt       3   6.570 ± 1.238  ops/ms
ClientPb.getUser                         thrpt       3   6.209 ± 1.239  ops/ms
ClientPb.listUser                        thrpt       3   5.218 ± 2.438  ops/ms
ClientPb.createUser                       avgt       3   5.183 ± 4.531   ms/op
ClientPb.existUser                        avgt       3   4.782 ± 2.587   ms/op
ClientPb.getUser                          avgt       3   5.180 ± 1.127   ms/op
ClientPb.listUser                         avgt       3   6.107 ± 6.871   ms/op
ClientPb.createUser                     sample  184642   5.198 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.038           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.830           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.538           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.725           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.376           ms/op
ClientPb.existUser                      sample  195843   4.903 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.450           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.241           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.554           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.766           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.227           ms/op
ClientPb.getUser                        sample  185379   5.174 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.239           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.948           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.250           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.437           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.183           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.678           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.026           ms/op
ClientPb.listUser                       sample  152373   6.296 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.806           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.013           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.907           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.834           ms/op
