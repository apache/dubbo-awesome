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
# Warmup Iteration   1: 1.152 ops/ms
# Warmup Iteration   2: 2.456 ops/ms
# Warmup Iteration   3: 5.143 ops/ms
Iteration   1: 5.553 ops/ms
Iteration   2: 5.498 ops/ms
Iteration   3: 5.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.522 ±(99.9%) 0.518 ops/ms [Average]
  (min, avg, max) = (5.498, 5.522, 5.553), stdev = 0.028
  CI (99.9%): [5.004, 6.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.812 ops/ms
# Warmup Iteration   2: 4.857 ops/ms
# Warmup Iteration   3: 5.964 ops/ms
Iteration   1: 5.753 ops/ms
Iteration   2: 5.883 ops/ms
Iteration   3: 5.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.865 ±(99.9%) 1.889 ops/ms [Average]
  (min, avg, max) = (5.753, 5.865, 5.958), stdev = 0.104
  CI (99.9%): [3.975, 7.754] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 4.394 ops/ms
# Warmup Iteration   3: 5.609 ops/ms
Iteration   1: 5.492 ops/ms
Iteration   2: 5.356 ops/ms
Iteration   3: 5.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.532 ±(99.9%) 3.648 ops/ms [Average]
  (min, avg, max) = (5.356, 5.532, 5.749), stdev = 0.200
  CI (99.9%): [1.884, 9.181] (assumes normal distribution)


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
# Warmup Iteration   1: 1.344 ops/ms
# Warmup Iteration   2: 3.831 ops/ms
# Warmup Iteration   3: 5.015 ops/ms
Iteration   1: 4.837 ops/ms
Iteration   2: 4.887 ops/ms
Iteration   3: 5.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.915 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (4.837, 4.915, 5.020), stdev = 0.095
  CI (99.9%): [3.187, 6.643] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 18.209 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 7.132 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.205 ±(99.9%) 0.007 ms/op
Iteration   1: 5.572 ±(99.9%) 0.013 ms/op
Iteration   2: 5.847 ±(99.9%) 0.009 ms/op
Iteration   3: 5.612 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.677 ±(99.9%) 2.711 ms/op [Average]
  (min, avg, max) = (5.572, 5.677, 5.847), stdev = 0.149
  CI (99.9%): [2.966, 8.388] (assumes normal distribution)


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
# Warmup Iteration   1: 16.346 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.452 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.635 ±(99.9%) 0.008 ms/op
Iteration   1: 5.315 ±(99.9%) 0.011 ms/op
Iteration   2: 5.531 ±(99.9%) 0.011 ms/op
Iteration   3: 5.375 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.407 ±(99.9%) 2.031 ms/op [Average]
  (min, avg, max) = (5.315, 5.407, 5.531), stdev = 0.111
  CI (99.9%): [3.377, 7.438] (assumes normal distribution)


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
# Warmup Iteration   1: 17.010 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.988 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.014 ms/op
Iteration   1: 6.074 ±(99.9%) 0.009 ms/op
Iteration   2: 5.593 ±(99.9%) 0.008 ms/op
Iteration   3: 5.519 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.729 ±(99.9%) 5.502 ms/op [Average]
  (min, avg, max) = (5.519, 5.729, 6.074), stdev = 0.302
  CI (99.9%): [0.227, 11.231] (assumes normal distribution)


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
# Warmup Iteration   1: 19.132 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 7.416 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.548 ±(99.9%) 0.009 ms/op
Iteration   1: 6.490 ±(99.9%) 0.011 ms/op
Iteration   2: 6.378 ±(99.9%) 0.011 ms/op
Iteration   3: 6.401 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.423 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (6.378, 6.423, 6.490), stdev = 0.059
  CI (99.9%): [5.340, 7.506] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.931 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 7.134 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.200 ±(99.9%) 0.029 ms/op
Iteration   1: 5.883 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.389 ms/op
                 createUser·p0.95:   8.159 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  24.180 ms/op
                 createUser·p0.9999: 30.734 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   2: 5.840 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.404 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.348 ms/op
                 createUser·p0.95:   8.241 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  25.763 ms/op
                 createUser·p0.9999: 29.458 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   3: 5.740 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.413 ms/op
                 createUser·p0.50:   5.505 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   7.840 ms/op
                 createUser·p0.99:   11.035 ms/op
                 createUser·p0.999:  27.494 ms/op
                 createUser·p0.9999: 35.679 ms/op
                 createUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164854
  mean =      5.820 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 49010 
    [ 5.000,  7.500) = 102327 
    [ 7.500, 10.000) = 11022 
    [10.000, 12.500) = 1571 
    [12.500, 15.000) = 401 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     25.597 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     36.969 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


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
# Warmup Iteration   1: 16.080 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 6.204 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.020 ms/op
Iteration   1: 5.179 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   7.119 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  22.497 ms/op
                 existUser·p0.9999: 29.753 ms/op
                 existUser·p1.00:   31.228 ms/op

Iteration   2: 5.294 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.127 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  18.401 ms/op
                 existUser·p0.9999: 29.491 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   3: 5.299 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.062 ms/op
                 existUser·p0.99:   9.519 ms/op
                 existUser·p0.999:  25.614 ms/op
                 existUser·p0.9999: 31.556 ms/op
                 existUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182488
  mean =      5.257 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 90322 
    [ 5.000,  7.500) = 85238 
    [ 7.500, 10.000) = 5275 
    [10.000, 12.500) = 1117 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.094 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     30.040 ms/op
     p(99.9990) =     31.856 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 17.784 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.434 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.021 ms/op
Iteration   1: 5.446 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.327 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   7.840 ms/op
                 getUser·p0.99:   10.875 ms/op
                 getUser·p0.999:  24.805 ms/op
                 getUser·p0.9999: 26.329 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 5.581 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.650 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   7.062 ms/op
                 getUser·p0.95:   8.241 ms/op
                 getUser·p0.99:   11.813 ms/op
                 getUser·p0.999:  25.395 ms/op
                 getUser·p0.9999: 30.026 ms/op
                 getUser·p1.00:   31.719 ms/op

Iteration   3: 5.611 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.955 ms/op
                 getUser·p0.95:   7.758 ms/op
                 getUser·p0.99:   10.371 ms/op
                 getUser·p0.999:  14.205 ms/op
                 getUser·p0.9999: 34.183 ms/op
                 getUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173061
  mean =      5.545 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 70291 
    [ 5.000,  7.500) = 90816 
    [ 7.500, 10.000) = 9199 
    [10.000, 12.500) = 1847 
    [12.500, 15.000) = 601 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.093 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.938 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     24.488 ms/op
     p(99.9900) =     33.479 ms/op
     p(99.9990) =     35.110 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 19.067 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 7.455 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.588 ±(99.9%) 0.025 ms/op
Iteration   1: 6.719 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.961 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   8.266 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   12.288 ms/op
                 listUser·p0.999:  24.543 ms/op
                 listUser·p0.9999: 29.348 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   2: 6.480 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.314 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   8.061 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   10.772 ms/op
                 listUser·p0.999:  26.137 ms/op
                 listUser·p0.9999: 30.642 ms/op
                 listUser·p1.00:   32.473 ms/op

Iteration   3: 6.428 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.241 ms/op
                 listUser·p0.99:   13.025 ms/op
                 listUser·p0.999:  26.023 ms/op
                 listUser·p0.9999: 30.836 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146787
  mean =      6.540 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 7218 
    [ 5.000,  7.500) = 114494 
    [ 7.500, 10.000) = 21321 
    [10.000, 12.500) = 2511 
    [12.500, 15.000) = 730 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      6.201 ms/op
     p(90.0000) =      8.135 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     25.671 ms/op
     p(99.9900) =     30.375 ms/op
     p(99.9990) =     33.273 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.522 ± 0.518  ops/ms
ClientPb.existUser                       thrpt       3   5.865 ± 1.889  ops/ms
ClientPb.getUser                         thrpt       3   5.532 ± 3.648  ops/ms
ClientPb.listUser                        thrpt       3   4.915 ± 1.728  ops/ms
ClientPb.createUser                       avgt       3   5.677 ± 2.711   ms/op
ClientPb.existUser                        avgt       3   5.407 ± 2.031   ms/op
ClientPb.getUser                          avgt       3   5.729 ± 5.502   ms/op
ClientPb.listUser                         avgt       3   6.423 ± 1.083   ms/op
ClientPb.createUser                     sample  164854   5.820 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.212           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.554           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.110           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.928           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.597           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.996           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.224           ms/op
ClientPb.existUser                      sample  182488   5.257 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.800           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.094           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.040           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  173061   5.545 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.093           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.938           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.076           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.488           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.479           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  146787   6.540 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.135           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.075           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.671           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.375           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.948           ms/op
