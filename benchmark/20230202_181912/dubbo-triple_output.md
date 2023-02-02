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
# Warmup Iteration   1: 0.960 ops/ms
# Warmup Iteration   2: 2.123 ops/ms
# Warmup Iteration   3: 4.870 ops/ms
Iteration   1: 5.285 ops/ms
Iteration   2: 5.647 ops/ms
Iteration   3: 5.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.507 ±(99.9%) 3.542 ops/ms [Average]
  (min, avg, max) = (5.285, 5.507, 5.647), stdev = 0.194
  CI (99.9%): [1.964, 9.049] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.565 ops/ms
# Warmup Iteration   2: 4.546 ops/ms
# Warmup Iteration   3: 5.688 ops/ms
Iteration   1: 5.763 ops/ms
Iteration   2: 5.824 ops/ms
Iteration   3: 5.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.800 ±(99.9%) 0.593 ops/ms [Average]
  (min, avg, max) = (5.763, 5.800, 5.824), stdev = 0.032
  CI (99.9%): [5.207, 6.393] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.552 ops/ms
# Warmup Iteration   2: 4.235 ops/ms
# Warmup Iteration   3: 5.513 ops/ms
Iteration   1: 5.595 ops/ms
Iteration   2: 5.501 ops/ms
Iteration   3: 5.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.595 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (5.501, 5.595, 5.688), stdev = 0.093
  CI (99.9%): [3.889, 7.300] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.481 ops/ms
# Warmup Iteration   2: 3.839 ops/ms
# Warmup Iteration   3: 4.615 ops/ms
Iteration   1: 4.481 ops/ms
Iteration   2: 4.784 ops/ms
Iteration   3: 4.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.670 ±(99.9%) 3.008 ops/ms [Average]
  (min, avg, max) = (4.481, 4.670, 4.784), stdev = 0.165
  CI (99.9%): [1.661, 7.678] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.425 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 7.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.942 ±(99.9%) 0.016 ms/op
Iteration   1: 5.659 ±(99.9%) 0.013 ms/op
Iteration   2: 6.016 ±(99.9%) 0.008 ms/op
Iteration   3: 5.704 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.793 ±(99.9%) 3.552 ms/op [Average]
  (min, avg, max) = (5.659, 5.793, 6.016), stdev = 0.195
  CI (99.9%): [2.241, 9.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 20.037 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.675 ±(99.9%) 0.006 ms/op
Iteration   1: 5.566 ±(99.9%) 0.009 ms/op
Iteration   2: 5.545 ±(99.9%) 0.007 ms/op
Iteration   3: 5.433 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.514 ±(99.9%) 1.308 ms/op [Average]
  (min, avg, max) = (5.433, 5.514, 5.566), stdev = 0.072
  CI (99.9%): [4.207, 6.822] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.092 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.387 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.935 ±(99.9%) 0.009 ms/op
Iteration   1: 5.993 ±(99.9%) 0.011 ms/op
Iteration   2: 5.631 ±(99.9%) 0.010 ms/op
Iteration   3: 5.676 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.767 ±(99.9%) 3.601 ms/op [Average]
  (min, avg, max) = (5.631, 5.767, 5.993), stdev = 0.197
  CI (99.9%): [2.166, 9.367] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.113 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 7.849 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.744 ±(99.9%) 0.011 ms/op
Iteration   1: 6.749 ±(99.9%) 0.009 ms/op
Iteration   2: 6.820 ±(99.9%) 0.012 ms/op
Iteration   3: 6.724 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.764 ±(99.9%) 0.906 ms/op [Average]
  (min, avg, max) = (6.724, 6.764, 6.820), stdev = 0.050
  CI (99.9%): [5.858, 7.670] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.886 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 7.724 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.711 ±(99.9%) 0.038 ms/op
Iteration   1: 5.875 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.897 ms/op
                 createUser·p0.95:   9.191 ms/op
                 createUser·p0.99:   12.009 ms/op
                 createUser·p0.999:  22.436 ms/op
                 createUser·p0.9999: 34.865 ms/op
                 createUser·p1.00:   35.455 ms/op

Iteration   2: 5.883 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.441 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   11.600 ms/op
                 createUser·p0.999:  27.205 ms/op
                 createUser·p0.9999: 31.869 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   3: 6.040 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   8.159 ms/op
                 createUser·p0.95:   9.535 ms/op
                 createUser·p0.99:   11.878 ms/op
                 createUser·p0.999:  20.709 ms/op
                 createUser·p0.9999: 34.826 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161768
  mean =      5.932 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 35286 
    [ 5.000,  7.500) = 107940 
    [ 7.500, 10.000) = 13391 
    [10.000, 12.500) = 3946 
    [12.500, 15.000) = 656 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.778 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.782 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     22.731 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     35.918 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 20.397 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 7.462 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 5.974 ±(99.9%) 0.026 ms/op
Iteration   1: 5.809 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.856 ms/op
                 existUser·p0.95:   9.322 ms/op
                 existUser·p0.99:   12.009 ms/op
                 existUser·p0.999:  28.736 ms/op
                 existUser·p0.9999: 32.538 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   2: 5.631 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.535 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   7.217 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.321 ms/op
                 existUser·p0.999:  16.564 ms/op
                 existUser·p0.9999: 30.405 ms/op
                 existUser·p1.00:   31.326 ms/op

Iteration   3: 5.969 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   2.066 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   8.143 ms/op
                 existUser·p0.95:   9.552 ms/op
                 existUser·p0.99:   14.451 ms/op
                 existUser·p0.999:  31.748 ms/op
                 existUser·p0.9999: 39.392 ms/op
                 existUser·p1.00:   45.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 165387
  mean =      5.799 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 53796 
    [ 5.000, 10.000) = 106395 
    [10.000, 15.000) = 4541 
    [15.000, 20.000) = 435 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 62 
    [30.000, 35.000) = 89 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      5.317 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      9.126 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     27.185 ms/op
     p(99.9900) =     36.962 ms/op
     p(99.9990) =     44.922 ms/op
     p(99.9999) =     45.351 ms/op
    p(100.0000) =     45.351 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.252 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 8.033 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 5.968 ±(99.9%) 0.022 ms/op
Iteration   1: 6.042 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   2.339 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   8.503 ms/op
                 getUser·p0.95:   10.060 ms/op
                 getUser·p0.99:   13.365 ms/op
                 getUser·p0.999:  29.138 ms/op
                 getUser·p0.9999: 32.271 ms/op
                 getUser·p1.00:   33.456 ms/op

Iteration   2: 5.817 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.807 ms/op
                 getUser·p0.95:   9.339 ms/op
                 getUser·p0.99:   12.933 ms/op
                 getUser·p0.999:  29.591 ms/op
                 getUser·p0.9999: 33.751 ms/op
                 getUser·p1.00:   35.848 ms/op

Iteration   3: 5.900 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   7.807 ms/op
                 getUser·p0.95:   9.519 ms/op
                 getUser·p0.99:   13.074 ms/op
                 getUser·p0.999:  28.410 ms/op
                 getUser·p0.9999: 36.083 ms/op
                 getUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162086
  mean =      5.918 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 45699 
    [ 5.000,  7.500) = 96612 
    [ 7.500, 10.000) = 12763 
    [10.000, 12.500) = 4902 
    [12.500, 15.000) = 1312 
    [15.000, 17.500) = 363 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 78 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      5.378 ms/op
     p(90.0000) =      8.055 ms/op
     p(95.0000) =      9.650 ms/op
     p(99.0000) =     13.091 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     33.958 ms/op
     p(99.9990) =     37.577 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 22.291 ±(99.9%) 0.434 ms/op
# Warmup Iteration   2: 9.071 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 7.102 ±(99.9%) 0.036 ms/op
Iteration   1: 7.090 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   10.158 ms/op
                 listUser·p0.95:   11.567 ms/op
                 listUser·p0.99:   14.680 ms/op
                 listUser·p0.999:  26.211 ms/op
                 listUser·p0.9999: 28.541 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   2: 6.972 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   9.634 ms/op
                 listUser·p0.95:   11.158 ms/op
                 listUser·p0.99:   16.127 ms/op
                 listUser·p0.999:  31.569 ms/op
                 listUser·p0.9999: 36.335 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   3: 7.153 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   10.060 ms/op
                 listUser·p0.95:   11.518 ms/op
                 listUser·p0.99:   15.450 ms/op
                 listUser·p0.999:  29.736 ms/op
                 listUser·p0.9999: 32.932 ms/op
                 listUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 135660
  mean =      7.071 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4217 
    [ 5.000,  7.500) = 97752 
    [ 7.500, 10.000) = 20365 
    [10.000, 12.500) = 8895 
    [12.500, 15.000) = 2911 
    [15.000, 17.500) = 845 
    [17.500, 20.000) = 289 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.785 ms/op
     p(50.0000) =      6.324 ms/op
     p(90.0000) =      9.961 ms/op
     p(95.0000) =     11.436 ms/op
     p(99.0000) =     15.335 ms/op
     p(99.9000) =     28.596 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     36.677 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.507 ± 3.542  ops/ms
ClientPb.existUser                       thrpt       3   5.800 ± 0.593  ops/ms
ClientPb.getUser                         thrpt       3   5.595 ± 1.706  ops/ms
ClientPb.listUser                        thrpt       3   4.670 ± 3.008  ops/ms
ClientPb.createUser                       avgt       3   5.793 ± 3.552   ms/op
ClientPb.existUser                        avgt       3   5.514 ± 1.308   ms/op
ClientPb.getUser                          avgt       3   5.767 ± 3.601   ms/op
ClientPb.listUser                         avgt       3   6.764 ± 0.906   ms/op
ClientPb.createUser                     sample  161768   5.932 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.778           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.782           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.126           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.796           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.731           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  165387   5.799 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.764           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.717           ms/op
ClientPb.existUser:existUser·p0.95      sample           9.126           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.288           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.185           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          45.351           ms/op
ClientPb.getUser                        sample  162086   5.918 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.561           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.378           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.650           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.091           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.131           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.958           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.618           ms/op
ClientPb.listUser                       sample  135660   7.071 ± 0.021   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.961           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.436           ms/op
ClientPb.listUser:listUser·p0.99        sample          15.335           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.596           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.324           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.700           ms/op
