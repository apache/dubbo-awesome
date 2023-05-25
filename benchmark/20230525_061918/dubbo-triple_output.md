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
# Warmup Iteration   1: 1.126 ops/ms
# Warmup Iteration   2: 2.562 ops/ms
# Warmup Iteration   3: 5.450 ops/ms
Iteration   1: 5.531 ops/ms
Iteration   2: 5.774 ops/ms
Iteration   3: 5.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.758 ±(99.9%) 4.015 ops/ms [Average]
  (min, avg, max) = (5.531, 5.758, 5.970), stdev = 0.220
  CI (99.9%): [1.744, 9.773] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.776 ops/ms
# Warmup Iteration   2: 5.135 ops/ms
# Warmup Iteration   3: 6.195 ops/ms
Iteration   1: 6.104 ops/ms
Iteration   2: 6.267 ops/ms
Iteration   3: 6.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.226 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (6.104, 6.226, 6.308), stdev = 0.108
  CI (99.9%): [4.261, 8.191] (assumes normal distribution)


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
# Warmup Iteration   1: 1.754 ops/ms
# Warmup Iteration   2: 5.021 ops/ms
# Warmup Iteration   3: 5.848 ops/ms
Iteration   1: 6.163 ops/ms
Iteration   2: 6.039 ops/ms
Iteration   3: 5.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.040 ±(99.9%) 2.237 ops/ms [Average]
  (min, avg, max) = (5.918, 6.040, 6.163), stdev = 0.123
  CI (99.9%): [3.802, 8.277] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.591 ops/ms
# Warmup Iteration   2: 4.048 ops/ms
# Warmup Iteration   3: 4.756 ops/ms
Iteration   1: 4.870 ops/ms
Iteration   2: 5.067 ops/ms
Iteration   3: 5.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.059 ±(99.9%) 3.370 ops/ms [Average]
  (min, avg, max) = (4.870, 5.059, 5.239), stdev = 0.185
  CI (99.9%): [1.688, 8.429] (assumes normal distribution)


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
# Warmup Iteration   1: 17.261 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.375 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.564 ±(99.9%) 0.014 ms/op
Iteration   1: 5.373 ±(99.9%) 0.025 ms/op
Iteration   2: 5.479 ±(99.9%) 0.018 ms/op
Iteration   3: 5.432 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.428 ±(99.9%) 0.973 ms/op [Average]
  (min, avg, max) = (5.373, 5.428, 5.479), stdev = 0.053
  CI (99.9%): [4.456, 6.401] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.718 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.109 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.034 ±(99.9%) 0.020 ms/op
Iteration   1: 5.184 ±(99.9%) 0.008 ms/op
Iteration   2: 5.057 ±(99.9%) 0.011 ms/op
Iteration   3: 5.187 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.142 ±(99.9%) 1.357 ms/op [Average]
  (min, avg, max) = (5.057, 5.142, 5.187), stdev = 0.074
  CI (99.9%): [3.786, 6.499] (assumes normal distribution)


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
# Warmup Iteration   1: 16.606 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.355 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.333 ±(99.9%) 0.017 ms/op
Iteration   1: 5.503 ±(99.9%) 0.011 ms/op
Iteration   2: 5.270 ±(99.9%) 0.017 ms/op
Iteration   3: 5.238 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.337 ±(99.9%) 2.638 ms/op [Average]
  (min, avg, max) = (5.238, 5.337, 5.503), stdev = 0.145
  CI (99.9%): [2.699, 7.975] (assumes normal distribution)


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
# Warmup Iteration   1: 18.815 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.777 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.448 ±(99.9%) 0.021 ms/op
Iteration   1: 6.143 ±(99.9%) 0.027 ms/op
Iteration   2: 6.303 ±(99.9%) 0.013 ms/op
Iteration   3: 6.610 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.352 ±(99.9%) 4.331 ms/op [Average]
  (min, avg, max) = (6.143, 6.352, 6.610), stdev = 0.237
  CI (99.9%): [2.021, 10.683] (assumes normal distribution)


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
# Warmup Iteration   1: 16.263 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.207 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.779 ±(99.9%) 0.027 ms/op
Iteration   1: 5.784 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.200 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  25.919 ms/op
                 createUser·p0.9999: 29.634 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   2: 5.729 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   8.069 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  28.172 ms/op
                 createUser·p0.9999: 31.719 ms/op
                 createUser·p1.00:   33.456 ms/op

Iteration   3: 5.631 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.404 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.864 ms/op
                 createUser·p0.99:   12.599 ms/op
                 createUser·p0.999:  31.326 ms/op
                 createUser·p0.9999: 34.755 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167890
  mean =      5.714 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 55275 
    [ 5.000,  7.500) = 99226 
    [ 7.500, 10.000) = 9555 
    [10.000, 12.500) = 2463 
    [12.500, 15.000) = 709 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 78 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.323 ms/op
     p(99.0000) =     11.977 ms/op
     p(99.9000) =     28.643 ms/op
     p(99.9900) =     33.634 ms/op
     p(99.9990) =     36.712 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.667 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.360 ±(99.9%) 0.019 ms/op
Iteration   1: 5.391 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.651 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   8.094 ms/op
                 existUser·p0.99:   10.371 ms/op
                 existUser·p0.999:  20.994 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   2: 5.361 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.097 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.701 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  24.008 ms/op
                 existUser·p0.9999: 29.298 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 5.204 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.398 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   9.788 ms/op
                 existUser·p0.999:  14.230 ms/op
                 existUser·p0.9999: 27.520 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180429
  mean =      5.317 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 88797 
    [ 5.000,  7.500) = 81511 
    [ 7.500, 10.000) = 7822 
    [10.000, 12.500) = 1530 
    [12.500, 15.000) = 415 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.619 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     15.970 ms/op
     p(99.9900) =     28.044 ms/op
     p(99.9990) =     29.746 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 16.249 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 6.061 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.387 ±(99.9%) 0.020 ms/op
Iteration   1: 5.658 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.731 ms/op
                 getUser·p0.50:   5.349 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   8.192 ms/op
                 getUser·p0.99:   12.141 ms/op
                 getUser·p0.999:  23.068 ms/op
                 getUser·p0.9999: 30.923 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   2: 5.593 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.048 ms/op
                 getUser·p0.95:   8.552 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  24.279 ms/op
                 getUser·p0.9999: 30.022 ms/op
                 getUser·p1.00:   32.473 ms/op

Iteration   3: 5.556 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.597 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   6.840 ms/op
                 getUser·p0.95:   7.766 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  15.499 ms/op
                 getUser·p0.9999: 29.333 ms/op
                 getUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171406
  mean =      5.602 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 58542 
    [ 5.000,  7.500) = 100509 
    [ 7.500, 10.000) = 9462 
    [10.000, 12.500) = 1889 
    [12.500, 15.000) = 585 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.731 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     29.674 ms/op
     p(99.9990) =     32.005 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 19.470 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 7.315 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.738 ±(99.9%) 0.028 ms/op
Iteration   1: 6.417 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  31.527 ms/op
                 listUser·p0.9999: 34.473 ms/op
                 listUser·p1.00:   38.142 ms/op

Iteration   2: 6.331 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.654 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   12.458 ms/op
                 listUser·p0.999:  31.488 ms/op
                 listUser·p0.9999: 34.133 ms/op
                 listUser·p1.00:   36.176 ms/op

Iteration   3: 6.321 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.039 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.302 ms/op
                 listUser·p0.999:  21.672 ms/op
                 listUser·p0.9999: 33.419 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151053
  mean =      6.356 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 8225 
    [ 5.000,  7.500) = 126879 
    [ 7.500, 10.000) = 11800 
    [10.000, 12.500) = 2888 
    [12.500, 15.000) = 702 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 116 
    [32.500, 35.000) = 64 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      6.046 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     33.941 ms/op
     p(99.9990) =     37.138 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.758 ± 4.015  ops/ms
ClientPb.existUser                       thrpt       3   6.226 ± 1.965  ops/ms
ClientPb.getUser                         thrpt       3   6.040 ± 2.237  ops/ms
ClientPb.listUser                        thrpt       3   5.059 ± 3.370  ops/ms
ClientPb.createUser                       avgt       3   5.428 ± 0.973   ms/op
ClientPb.existUser                        avgt       3   5.142 ± 1.357   ms/op
ClientPb.getUser                          avgt       3   5.337 ± 2.638   ms/op
ClientPb.listUser                         avgt       3   6.352 ± 4.331   ms/op
ClientPb.createUser                     sample  167890   5.714 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.179           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.323           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.977           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.643           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.634           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  180429   5.317 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.421           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.619           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.355           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.970           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.044           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.852           ms/op
ClientPb.getUser                        sample  171406   5.602 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.731           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.292           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.143           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.692           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.674           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.473           ms/op
ClientPb.listUser                       sample  151053   6.356 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.046           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.700           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.704           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.941           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.142           ms/op
