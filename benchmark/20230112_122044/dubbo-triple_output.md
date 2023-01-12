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
# Warmup Iteration   1: 1.007 ops/ms
# Warmup Iteration   2: 2.403 ops/ms
# Warmup Iteration   3: 5.269 ops/ms
Iteration   1: 5.647 ops/ms
Iteration   2: 5.523 ops/ms
Iteration   3: 5.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.648 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (5.523, 5.648, 5.774), stdev = 0.126
  CI (99.9%): [3.358, 7.939] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.652 ops/ms
# Warmup Iteration   2: 4.625 ops/ms
# Warmup Iteration   3: 5.828 ops/ms
Iteration   1: 6.114 ops/ms
Iteration   2: 6.145 ops/ms
Iteration   3: 5.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.018 ±(99.9%) 3.543 ops/ms [Average]
  (min, avg, max) = (5.794, 6.018, 6.145), stdev = 0.194
  CI (99.9%): [2.475, 9.561] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.477 ops/ms
# Warmup Iteration   2: 4.160 ops/ms
# Warmup Iteration   3: 5.397 ops/ms
Iteration   1: 5.093 ops/ms
Iteration   2: 5.293 ops/ms
Iteration   3: 5.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.233 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (5.093, 5.233, 5.315), stdev = 0.122
  CI (99.9%): [3.001, 7.466] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.256 ops/ms
# Warmup Iteration   2: 3.319 ops/ms
# Warmup Iteration   3: 4.397 ops/ms
Iteration   1: 4.410 ops/ms
Iteration   2: 4.540 ops/ms
Iteration   3: 4.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.460 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (4.410, 4.460, 4.540), stdev = 0.070
  CI (99.9%): [3.188, 5.732] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 22.554 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.569 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.278 ±(99.9%) 0.013 ms/op
Iteration   1: 6.261 ±(99.9%) 0.021 ms/op
Iteration   2: 5.989 ±(99.9%) 0.018 ms/op
Iteration   3: 5.975 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.075 ±(99.9%) 2.940 ms/op [Average]
  (min, avg, max) = (5.975, 6.075, 6.261), stdev = 0.161
  CI (99.9%): [3.135, 9.015] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.068 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 7.156 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.555 ±(99.9%) 0.016 ms/op
Iteration   1: 5.740 ±(99.9%) 0.015 ms/op
Iteration   2: 5.211 ±(99.9%) 0.015 ms/op
Iteration   3: 5.156 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.369 ±(99.9%) 5.885 ms/op [Average]
  (min, avg, max) = (5.156, 5.369, 5.740), stdev = 0.323
  CI (99.9%): [≈ 0, 11.254] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 17.238 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.470 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.687 ±(99.9%) 0.011 ms/op
Iteration   1: 6.163 ±(99.9%) 0.010 ms/op
Iteration   2: 5.689 ±(99.9%) 0.015 ms/op
Iteration   3: 5.489 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.780 ±(99.9%) 6.316 ms/op [Average]
  (min, avg, max) = (5.489, 5.780, 6.163), stdev = 0.346
  CI (99.9%): [≈ 0, 12.096] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.755 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 8.325 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.447 ±(99.9%) 0.012 ms/op
Iteration   1: 6.281 ±(99.9%) 0.011 ms/op
Iteration   2: 6.315 ±(99.9%) 0.019 ms/op
Iteration   3: 6.497 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.365 ±(99.9%) 2.120 ms/op [Average]
  (min, avg, max) = (6.281, 6.365, 6.497), stdev = 0.116
  CI (99.9%): [4.245, 8.485] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.221 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 7.219 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.352 ±(99.9%) 0.034 ms/op
Iteration   1: 5.609 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.758 ms/op
                 createUser·p0.95:   7.676 ms/op
                 createUser·p0.99:   11.525 ms/op
                 createUser·p0.999:  23.524 ms/op
                 createUser·p0.9999: 26.702 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   2: 5.720 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.962 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.045 ms/op
                 createUser·p0.95:   7.841 ms/op
                 createUser·p0.99:   11.403 ms/op
                 createUser·p0.999:  25.695 ms/op
                 createUser·p0.9999: 29.846 ms/op
                 createUser·p1.00:   30.114 ms/op

Iteration   3: 5.505 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.636 ms/op
                 createUser·p0.95:   7.258 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  14.824 ms/op
                 createUser·p0.9999: 28.415 ms/op
                 createUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170947
  mean =      5.610 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 57784 
    [ 5.000,  7.500) = 104096 
    [ 7.500, 10.000) = 6603 
    [10.000, 12.500) = 1461 
    [12.500, 15.000) = 557 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.944 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     20.926 ms/op
     p(99.9900) =     28.624 ms/op
     p(99.9990) =     33.069 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.601 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 6.048 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.452 ±(99.9%) 0.020 ms/op
Iteration   1: 5.266 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.531 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  22.249 ms/op
                 existUser·p0.9999: 25.819 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 5.435 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   5.054 ms/op
                 existUser·p0.90:   6.799 ms/op
                 existUser·p0.95:   7.774 ms/op
                 existUser·p0.99:   10.921 ms/op
                 existUser·p0.999:  23.069 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 5.204 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.106 ms/op
                 existUser·p0.99:   9.175 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180982
  mean =      5.300 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 94055 
    [ 5.000,  7.500) = 78610 
    [ 7.500, 10.000) = 6300 
    [10.000, 12.500) = 1385 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     25.880 ms/op
     p(99.9990) =     28.442 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.948 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 6.677 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.788 ±(99.9%) 0.024 ms/op
Iteration   1: 5.422 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   7.700 ms/op
                 getUser·p0.99:   10.568 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 29.622 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 5.723 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.544 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   7.422 ms/op
                 getUser·p0.95:   8.700 ms/op
                 getUser·p0.99:   11.878 ms/op
                 getUser·p0.999:  19.661 ms/op
                 getUser·p0.9999: 29.321 ms/op
                 getUser·p1.00:   32.539 ms/op

Iteration   3: 5.703 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.414 ms/op
                 getUser·p0.95:   8.331 ms/op
                 getUser·p0.99:   11.158 ms/op
                 getUser·p0.999:  29.000 ms/op
                 getUser·p0.9999: 32.519 ms/op
                 getUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171067
  mean =      5.612 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 65330 
    [ 5.000,  7.500) = 91572 
    [ 7.500, 10.000) = 10981 
    [10.000, 12.500) = 2250 
    [12.500, 15.000) = 553 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.212 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     32.007 ms/op
     p(99.9990) =     33.177 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 18.873 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 7.836 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.692 ±(99.9%) 0.030 ms/op
Iteration   1: 6.542 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.064 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   12.190 ms/op
                 listUser·p0.999:  29.724 ms/op
                 listUser·p0.9999: 32.517 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   2: 6.424 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.925 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.717 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   12.330 ms/op
                 listUser·p0.999:  29.196 ms/op
                 listUser·p0.9999: 33.949 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 6.356 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   12.321 ms/op
                 listUser·p0.999:  23.873 ms/op
                 listUser·p0.9999: 27.489 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148983
  mean =      6.440 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 8128 
    [ 5.000,  7.500) = 120990 
    [ 7.500, 10.000) = 16081 
    [10.000, 12.500) = 2485 
    [12.500, 15.000) = 723 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.691 ms/op
     p(50.0000) =      6.103 ms/op
     p(90.0000) =      7.881 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     12.241 ms/op
     p(99.9000) =     28.213 ms/op
     p(99.9900) =     33.561 ms/op
     p(99.9990) =     34.346 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.648 ± 2.290  ops/ms
ClientPb.existUser                       thrpt       3   6.018 ± 3.543  ops/ms
ClientPb.getUser                         thrpt       3   5.233 ± 2.233  ops/ms
ClientPb.listUser                        thrpt       3   4.460 ± 1.272  ops/ms
ClientPb.createUser                       avgt       3   6.075 ± 2.940   ms/op
ClientPb.existUser                        avgt       3   5.369 ± 5.885   ms/op
ClientPb.getUser                          avgt       3   5.780 ± 6.316   ms/op
ClientPb.listUser                         avgt       3   6.365 ± 2.120   ms/op
ClientPb.createUser                     sample  170947   5.610 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.944           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.076           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.926           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.624           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.603           ms/op
ClientPb.existUser                      sample  180982   5.300 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.106           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.240           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.808           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.880           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.557           ms/op
ClientPb.getUser                        sample  171067   5.612 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.235           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.289           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.775           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.456           ms/op
ClientPb.listUser                       sample  148983   6.440 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.691           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.881           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.213           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.603           ms/op
