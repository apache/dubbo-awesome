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
# Warmup Iteration   1: 1.628 ops/ms
# Warmup Iteration   2: 4.001 ops/ms
# Warmup Iteration   3: 7.191 ops/ms
Iteration   1: 7.609 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.789 ±(99.9%) 4.060 ops/ms [Average]
  (min, avg, max) = (7.609, 7.789, 8.038), stdev = 0.223
  CI (99.9%): [3.729, 11.849] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.515 ops/ms
# Warmup Iteration   2: 6.633 ops/ms
# Warmup Iteration   3: 8.094 ops/ms
Iteration   1: 8.400 ops/ms
Iteration   2: 8.515 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.423 ±(99.9%) 1.514 ops/ms [Average]
  (min, avg, max) = (8.354, 8.423, 8.515), stdev = 0.083
  CI (99.9%): [6.909, 9.937] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.274 ops/ms
# Warmup Iteration   2: 6.669 ops/ms
# Warmup Iteration   3: 7.669 ops/ms
Iteration   1: 7.598 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 8.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.932 ±(99.9%) 5.351 ops/ms [Average]
  (min, avg, max) = (7.598, 7.932, 8.147), stdev = 0.293
  CI (99.9%): [2.581, 13.283] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 5.460 ops/ms
# Warmup Iteration   3: 6.462 ops/ms
Iteration   1: 6.656 ops/ms
Iteration   2: 6.568 ops/ms
Iteration   3: 6.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.611 ±(99.9%) 0.806 ops/ms [Average]
  (min, avg, max) = (6.568, 6.611, 6.656), stdev = 0.044
  CI (99.9%): [5.805, 7.417] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.286 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.004 ms/op
Iteration   1: 4.122 ±(99.9%) 0.004 ms/op
Iteration   2: 4.081 ±(99.9%) 0.002 ms/op
Iteration   3: 4.021 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.075 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (4.021, 4.075, 4.122), stdev = 0.051
  CI (99.9%): [3.148, 5.001] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.761 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.004 ms/op
Iteration   1: 3.900 ±(99.9%) 0.006 ms/op
Iteration   2: 3.809 ±(99.9%) 0.003 ms/op
Iteration   3: 3.773 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.827 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (3.773, 3.827, 3.900), stdev = 0.065
  CI (99.9%): [2.632, 5.022] (assumes normal distribution)


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
# Warmup Iteration   1: 13.477 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.611 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.003 ms/op
Iteration   1: 3.972 ±(99.9%) 0.003 ms/op
Iteration   2: 4.134 ±(99.9%) 0.004 ms/op
Iteration   3: 4.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.042 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.972, 4.042, 4.134), stdev = 0.083
  CI (99.9%): [2.521, 5.563] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.962 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.008 ms/op
Iteration   1: 4.749 ±(99.9%) 0.009 ms/op
Iteration   2: 4.787 ±(99.9%) 0.008 ms/op
Iteration   3: 4.770 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.769 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (4.749, 4.769, 4.787), stdev = 0.019
  CI (99.9%): [4.420, 5.118] (assumes normal distribution)


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
# Warmup Iteration   1: 13.975 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.015 ms/op
Iteration   1: 4.022 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.030 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  21.970 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.909 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   7.441 ms/op
                 createUser·p0.999:  24.543 ms/op
                 createUser·p0.9999: 26.247 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.909 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  16.953 ms/op
                 createUser·p0.9999: 29.197 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238330
  mean =      4.030 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 175 
    [ 2.500,  5.000) = 228165 
    [ 5.000,  7.500) = 7908 
    [ 7.500, 10.000) = 1207 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.909 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     29.642 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 11.821 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.012 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 25.097 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.881 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  15.305 ms/op
                 existUser·p0.9999: 26.724 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.843 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   7.127 ms/op
                 existUser·p0.999:  26.837 ms/op
                 existUser·p0.9999: 29.841 ms/op
                 existUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246552
  mean =      3.893 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 432 
    [ 2.500,  5.000) = 234660 
    [ 5.000,  7.500) = 9466 
    [ 7.500, 10.000) = 1406 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.350 ms/op
     p(99.9900) =     28.847 ms/op
     p(99.9990) =     30.066 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 10.833 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.325 ±(99.9%) 0.015 ms/op
Iteration   1: 3.998 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.243 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  14.287 ms/op
                 getUser·p0.9999: 26.476 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.081 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.950 ms/op
                 getUser·p0.999:  26.935 ms/op
                 getUser·p0.9999: 30.441 ms/op
                 getUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241306
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 232924 
    [ 5.000,  7.500) = 6295 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 325 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 112 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     23.527 ms/op
     p(99.9900) =     29.061 ms/op
     p(99.9990) =     30.958 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 16.408 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.660 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.875 ±(99.9%) 0.017 ms/op
Iteration   1: 4.916 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 28.033 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.955 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.888 ms/op
                 listUser·p0.999:  19.810 ms/op
                 listUser·p0.9999: 23.218 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.763 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  17.097 ms/op
                 listUser·p0.9999: 19.048 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196612
  mean =      4.876 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 143660 
    [ 5.000,  7.500) = 48643 
    [ 7.500, 10.000) = 3045 
    [10.000, 12.500) = 530 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.520 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     19.535 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     28.317 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.789 ± 4.060  ops/ms
ClientPb.existUser                       thrpt       3   8.423 ± 1.514  ops/ms
ClientPb.getUser                         thrpt       3   7.932 ± 5.351  ops/ms
ClientPb.listUser                        thrpt       3   6.611 ± 0.806  ops/ms
ClientPb.createUser                       avgt       3   4.075 ± 0.926   ms/op
ClientPb.existUser                        avgt       3   3.827 ± 1.195   ms/op
ClientPb.getUser                          avgt       3   4.042 ± 1.521   ms/op
ClientPb.listUser                         avgt       3   4.769 ± 0.349   ms/op
ClientPb.createUser                     sample  238330   4.030 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.909           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.053           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.738           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.376           ms/op
ClientPb.existUser                      sample  246552   3.893 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.423           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.062           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.350           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.847           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.278           ms/op
ClientPb.getUser                        sample  241306   3.977 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.243           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.225           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.527           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.061           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  196612   4.876 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.520           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.132           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
