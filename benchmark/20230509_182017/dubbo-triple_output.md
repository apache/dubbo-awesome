# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.096 ops/ms
# Warmup Iteration   2: 2.731 ops/ms
# Warmup Iteration   3: 5.620 ops/ms
Iteration   1: 5.568 ops/ms
Iteration   2: 5.808 ops/ms
Iteration   3: 5.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.759 ±(99.9%) 3.122 ops/ms [Average]
  (min, avg, max) = (5.568, 5.759, 5.899), stdev = 0.171
  CI (99.9%): [2.636, 8.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.732 ops/ms
# Warmup Iteration   2: 4.857 ops/ms
# Warmup Iteration   3: 5.867 ops/ms
Iteration   1: 6.166 ops/ms
Iteration   2: 6.001 ops/ms
Iteration   3: 5.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.036 ±(99.9%) 2.133 ops/ms [Average]
  (min, avg, max) = (5.941, 6.036, 6.166), stdev = 0.117
  CI (99.9%): [3.903, 8.169] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.500 ops/ms
# Warmup Iteration   2: 4.635 ops/ms
# Warmup Iteration   3: 5.914 ops/ms
Iteration   1: 6.071 ops/ms
Iteration   2: 5.617 ops/ms
Iteration   3: 5.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.854 ±(99.9%) 4.156 ops/ms [Average]
  (min, avg, max) = (5.617, 5.854, 6.071), stdev = 0.228
  CI (99.9%): [1.698, 10.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 4.128 ops/ms
# Warmup Iteration   3: 4.967 ops/ms
Iteration   1: 5.120 ops/ms
Iteration   2: 4.960 ops/ms
Iteration   3: 5.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.156 ±(99.9%) 3.941 ops/ms [Average]
  (min, avg, max) = (4.960, 5.156, 5.388), stdev = 0.216
  CI (99.9%): [1.215, 9.097] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.237 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.220 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.339 ±(99.9%) 0.014 ms/op
Iteration   1: 5.478 ±(99.9%) 0.009 ms/op
Iteration   2: 5.435 ±(99.9%) 0.012 ms/op
Iteration   3: 5.448 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.454 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (5.435, 5.454, 5.478), stdev = 0.022
  CI (99.9%): [5.055, 5.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.380 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.747 ±(99.9%) 0.010 ms/op
Iteration   1: 5.398 ±(99.9%) 0.011 ms/op
Iteration   2: 5.231 ±(99.9%) 0.015 ms/op
Iteration   3: 5.358 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.329 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (5.231, 5.329, 5.398), stdev = 0.087
  CI (99.9%): [3.741, 6.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.392 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.314 ±(99.9%) 0.006 ms/op
Iteration   1: 4.943 ±(99.9%) 0.011 ms/op
Iteration   2: 5.391 ±(99.9%) 0.009 ms/op
Iteration   3: 5.061 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.132 ±(99.9%) 4.237 ms/op [Average]
  (min, avg, max) = (4.943, 5.132, 5.391), stdev = 0.232
  CI (99.9%): [0.895, 9.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.696 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 7.647 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.098 ±(99.9%) 0.013 ms/op
Iteration   1: 5.990 ±(99.9%) 0.015 ms/op
Iteration   2: 5.861 ±(99.9%) 0.014 ms/op
Iteration   3: 5.836 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.896 ±(99.9%) 1.501 ms/op [Average]
  (min, avg, max) = (5.836, 5.896, 5.990), stdev = 0.082
  CI (99.9%): [4.394, 7.397] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.404 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 6.288 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.025 ms/op
Iteration   1: 5.352 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.365 ms/op
                 createUser·p0.99:   9.847 ms/op
                 createUser·p0.999:  13.681 ms/op
                 createUser·p0.9999: 27.395 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   2: 5.300 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.220 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   9.273 ms/op
                 createUser·p0.999:  24.389 ms/op
                 createUser·p0.9999: 28.340 ms/op
                 createUser·p1.00:   30.179 ms/op

Iteration   3: 5.396 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.652 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  26.294 ms/op
                 createUser·p0.9999: 29.957 ms/op
                 createUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179483
  mean =      5.349 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 76660 
    [ 5.000,  7.500) = 95213 
    [ 7.500, 10.000) = 6063 
    [10.000, 12.500) = 1081 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     15.278 ms/op
     p(99.9900) =     29.427 ms/op
     p(99.9990) =     30.514 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.644 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.036 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.020 ms/op
Iteration   1: 5.134 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.009 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  22.835 ms/op
                 existUser·p0.9999: 25.222 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   2: 5.071 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.187 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.234 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   9.994 ms/op
                 existUser·p0.999:  16.479 ms/op
                 existUser·p0.9999: 28.203 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   3: 5.316 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.458 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   7.741 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  25.226 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185545
  mean =      5.172 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 104320 
    [ 5.000,  7.500) = 72135 
    [ 7.500, 10.000) = 6922 
    [10.000, 12.500) = 1158 
    [12.500, 15.000) = 589 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.725 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.265 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.207 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.678 ±(99.9%) 0.021 ms/op
Iteration   1: 5.421 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.142 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.775 ms/op
                 getUser·p0.95:   7.799 ms/op
                 getUser·p0.99:   10.966 ms/op
                 getUser·p0.999:  24.183 ms/op
                 getUser·p0.9999: 27.397 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 5.479 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.794 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   10.813 ms/op
                 getUser·p0.999:  24.680 ms/op
                 getUser·p0.9999: 31.309 ms/op
                 getUser·p1.00:   33.096 ms/op

Iteration   3: 5.352 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.964 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.512 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  26.224 ms/op
                 getUser·p0.9999: 30.803 ms/op
                 getUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177084
  mean =      5.417 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 77239 
    [ 5.000,  7.500) = 89538 
    [ 7.500, 10.000) = 7997 
    [10.000, 12.500) = 1441 
    [12.500, 15.000) = 422 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.767 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     33.426 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.714 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 7.383 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.235 ±(99.9%) 0.022 ms/op
Iteration   1: 6.375 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.503 ms/op
                 listUser·p0.50:   6.062 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  26.235 ms/op
                 listUser·p0.9999: 29.457 ms/op
                 listUser·p1.00:   31.687 ms/op

Iteration   2: 5.938 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   5.644 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   11.737 ms/op
                 listUser·p0.999:  26.593 ms/op
                 listUser·p0.9999: 30.169 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   3: 6.047 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.941 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.258 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  24.805 ms/op
                 listUser·p0.9999: 30.899 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156944
  mean =      6.114 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 21770 
    [ 5.000,  7.500) = 120640 
    [ 7.500, 10.000) = 11196 
    [10.000, 12.500) = 2310 
    [12.500, 15.000) = 547 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 151 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      5.849 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     30.199 ms/op
     p(99.9990) =     32.127 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.759 ± 3.122  ops/ms
ClientPb.existUser                       thrpt       3   6.036 ± 2.133  ops/ms
ClientPb.getUser                         thrpt       3   5.854 ± 4.156  ops/ms
ClientPb.listUser                        thrpt       3   5.156 ± 3.941  ops/ms
ClientPb.createUser                       avgt       3   5.454 ± 0.399   ms/op
ClientPb.existUser                        avgt       3   5.329 ± 1.588   ms/op
ClientPb.getUser                          avgt       3   5.132 ± 4.237   ms/op
ClientPb.listUser                         avgt       3   5.896 ± 1.501   ms/op
ClientPb.createUser                     sample  179483   5.349 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.568           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.278           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.427           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.540           ms/op
ClientPb.existUser                      sample  185545   5.172 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.009           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.471           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.420           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.694           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.753           ms/op
ClientPb.getUser                        sample  177084   5.417 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.717           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.216           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  156944   6.114 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.466           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.551           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.116           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.199           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.145           ms/op
