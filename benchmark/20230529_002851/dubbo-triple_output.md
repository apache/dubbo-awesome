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
# Warmup Iteration   1: 1.045 ops/ms
# Warmup Iteration   2: 2.261 ops/ms
# Warmup Iteration   3: 4.709 ops/ms
Iteration   1: 5.297 ops/ms
Iteration   2: 5.435 ops/ms
Iteration   3: 5.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.481 ±(99.9%) 3.845 ops/ms [Average]
  (min, avg, max) = (5.297, 5.481, 5.711), stdev = 0.211
  CI (99.9%): [1.636, 9.326] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.583 ops/ms
# Warmup Iteration   2: 4.116 ops/ms
# Warmup Iteration   3: 5.537 ops/ms
Iteration   1: 5.844 ops/ms
Iteration   2: 5.994 ops/ms
Iteration   3: 6.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.982 ±(99.9%) 2.406 ops/ms [Average]
  (min, avg, max) = (5.844, 5.982, 6.107), stdev = 0.132
  CI (99.9%): [3.576, 8.387] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.468 ops/ms
# Warmup Iteration   2: 4.208 ops/ms
# Warmup Iteration   3: 5.632 ops/ms
Iteration   1: 5.679 ops/ms
Iteration   2: 5.641 ops/ms
Iteration   3: 5.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.724 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (5.641, 5.724, 5.854), stdev = 0.114
  CI (99.9%): [3.649, 7.799] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.520 ops/ms
# Warmup Iteration   2: 4.095 ops/ms
# Warmup Iteration   3: 4.796 ops/ms
Iteration   1: 4.976 ops/ms
Iteration   2: 4.899 ops/ms
Iteration   3: 4.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.861 ±(99.9%) 2.512 ops/ms [Average]
  (min, avg, max) = (4.708, 4.861, 4.976), stdev = 0.138
  CI (99.9%): [2.349, 7.373] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 20.545 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 7.003 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.794 ±(99.9%) 0.016 ms/op
Iteration   1: 6.073 ±(99.9%) 0.009 ms/op
Iteration   2: 5.603 ±(99.9%) 0.013 ms/op
Iteration   3: 5.676 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.784 ±(99.9%) 4.608 ms/op [Average]
  (min, avg, max) = (5.603, 5.784, 6.073), stdev = 0.253
  CI (99.9%): [1.176, 10.392] (assumes normal distribution)


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
# Warmup Iteration   1: 16.713 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 7.134 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.012 ms/op
Iteration   1: 5.482 ±(99.9%) 0.013 ms/op
Iteration   2: 5.470 ±(99.9%) 0.009 ms/op
Iteration   3: 5.363 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.438 ±(99.9%) 1.186 ms/op [Average]
  (min, avg, max) = (5.363, 5.438, 5.482), stdev = 0.065
  CI (99.9%): [4.252, 6.625] (assumes normal distribution)


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
# Warmup Iteration   1: 19.572 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.968 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.707 ±(99.9%) 0.007 ms/op
Iteration   1: 5.724 ±(99.9%) 0.010 ms/op
Iteration   2: 5.812 ±(99.9%) 0.009 ms/op
Iteration   3: 5.628 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.721 ±(99.9%) 1.682 ms/op [Average]
  (min, avg, max) = (5.628, 5.721, 5.812), stdev = 0.092
  CI (99.9%): [4.039, 7.403] (assumes normal distribution)


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
# Warmup Iteration   1: 23.440 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 8.119 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.624 ±(99.9%) 0.018 ms/op
Iteration   1: 6.777 ±(99.9%) 0.010 ms/op
Iteration   2: 6.572 ±(99.9%) 0.015 ms/op
Iteration   3: 6.663 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.671 ±(99.9%) 1.874 ms/op [Average]
  (min, avg, max) = (6.572, 6.671, 6.777), stdev = 0.103
  CI (99.9%): [4.797, 8.545] (assumes normal distribution)


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
# Warmup Iteration   1: 20.755 ±(99.9%) 0.344 ms/op
# Warmup Iteration   2: 7.196 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.280 ±(99.9%) 0.031 ms/op
Iteration   1: 5.788 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   7.217 ms/op
                 createUser·p0.95:   8.618 ms/op
                 createUser·p0.99:   11.878 ms/op
                 createUser·p0.999:  26.247 ms/op
                 createUser·p0.9999: 36.486 ms/op
                 createUser·p1.00:   38.076 ms/op

Iteration   2: 5.836 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.258 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   12.534 ms/op
                 createUser·p0.999:  24.262 ms/op
                 createUser·p0.9999: 29.132 ms/op
                 createUser·p1.00:   29.786 ms/op

Iteration   3: 5.792 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.742 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.312 ms/op
                 createUser·p0.99:   11.256 ms/op
                 createUser·p0.999:  32.327 ms/op
                 createUser·p0.9999: 34.896 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 165338
  mean =      5.806 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 42515 
    [ 5.000,  7.500) = 108858 
    [ 7.500, 10.000) = 10022 
    [10.000, 12.500) = 2617 
    [12.500, 15.000) = 818 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 56 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      7.234 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     25.887 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     37.819 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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
# Warmup Iteration   1: 15.950 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.340 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.823 ±(99.9%) 0.027 ms/op
Iteration   1: 5.388 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  16.517 ms/op
                 existUser·p0.9999: 28.386 ms/op
                 existUser·p1.00:   30.900 ms/op

Iteration   2: 5.480 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.621 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.619 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  14.716 ms/op
                 existUser·p0.9999: 29.491 ms/op
                 existUser·p1.00:   29.917 ms/op

Iteration   3: 5.651 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.400 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.176 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   11.731 ms/op
                 existUser·p0.999:  29.323 ms/op
                 existUser·p0.9999: 33.489 ms/op
                 existUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174276
  mean =      5.504 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 64629 
    [ 5.000,  7.500) = 99051 
    [ 7.500, 10.000) = 8260 
    [10.000, 12.500) = 1526 
    [12.500, 15.000) = 398 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.400 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     22.666 ms/op
     p(99.9900) =     32.337 ms/op
     p(99.9990) =     34.281 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.598 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.731 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.636 ±(99.9%) 0.019 ms/op
Iteration   1: 5.955 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   7.889 ms/op
                 getUser·p0.95:   9.585 ms/op
                 getUser·p0.99:   14.029 ms/op
                 getUser·p0.999:  26.604 ms/op
                 getUser·p0.9999: 32.428 ms/op
                 getUser·p1.00:   32.801 ms/op

Iteration   2: 5.735 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.307 ms/op
                 getUser·p0.95:   8.441 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  29.319 ms/op
                 getUser·p0.9999: 33.080 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   3: 5.737 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.687 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   8.110 ms/op
                 getUser·p0.99:   10.560 ms/op
                 getUser·p0.999:  14.696 ms/op
                 getUser·p0.9999: 31.499 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165278
  mean =      5.808 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 46142 
    [ 5.000,  7.500) = 103662 
    [ 7.500, 10.000) = 11320 
    [10.000, 12.500) = 2831 
    [12.500, 15.000) = 779 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 83 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      5.399 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.700 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     32.423 ms/op
     p(99.9990) =     33.734 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 20.842 ±(99.9%) 0.370 ms/op
# Warmup Iteration   2: 8.189 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.876 ±(99.9%) 0.031 ms/op
Iteration   1: 6.681 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   8.372 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   13.369 ms/op
                 listUser·p0.999:  25.662 ms/op
                 listUser·p0.9999: 28.424 ms/op
                 listUser·p1.00:   30.769 ms/op

Iteration   2: 6.895 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   8.733 ms/op
                 listUser·p0.95:   10.437 ms/op
                 listUser·p0.99:   15.122 ms/op
                 listUser·p0.999:  28.672 ms/op
                 listUser·p0.9999: 32.794 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   3: 6.805 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.687 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   8.372 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.681 ms/op
                 listUser·p0.999:  25.232 ms/op
                 listUser·p0.9999: 28.790 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141237
  mean =      6.792 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 3812 
    [ 5.000,  7.500) = 112148 
    [ 7.500, 10.000) = 18177 
    [10.000, 12.500) = 4842 
    [12.500, 15.000) = 1251 
    [15.000, 17.500) = 489 
    [17.500, 20.000) = 203 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.761 ms/op
     p(50.0000) =      6.324 ms/op
     p(90.0000) =      8.503 ms/op
     p(95.0000) =     10.011 ms/op
     p(99.0000) =     13.959 ms/op
     p(99.9000) =     26.658 ms/op
     p(99.9900) =     31.314 ms/op
     p(99.9990) =     33.146 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.481 ± 3.845  ops/ms
ClientPb.existUser                       thrpt       3   5.982 ± 2.406  ops/ms
ClientPb.getUser                         thrpt       3   5.724 ± 2.075  ops/ms
ClientPb.listUser                        thrpt       3   4.861 ± 2.512  ops/ms
ClientPb.createUser                       avgt       3   5.784 ± 4.608   ms/op
ClientPb.existUser                        avgt       3   5.438 ± 1.186   ms/op
ClientPb.getUser                          avgt       3   5.721 ± 1.682   ms/op
ClientPb.listUser                         avgt       3   6.671 ± 1.874   ms/op
ClientPb.createUser                     sample  165338   5.806 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.742           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.431           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.234           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.454           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.829           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.887           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.062           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  174276   5.504 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.400           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.726           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.864           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.437           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.666           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.865           ms/op
ClientPb.getUser                        sample  165278   5.808 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.964           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.399           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.397           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.700           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.895           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.362           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.423           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  141237   6.792 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.324           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.011           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.959           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.658           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.314           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
