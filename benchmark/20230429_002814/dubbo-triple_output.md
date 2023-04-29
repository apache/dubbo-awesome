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
# Warmup Iteration   1: 0.979 ops/ms
# Warmup Iteration   2: 2.220 ops/ms
# Warmup Iteration   3: 4.502 ops/ms
Iteration   1: 5.176 ops/ms
Iteration   2: 5.272 ops/ms
Iteration   3: 5.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.305 ±(99.9%) 2.701 ops/ms [Average]
  (min, avg, max) = (5.176, 5.305, 5.466), stdev = 0.148
  CI (99.9%): [2.604, 8.006] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.638 ops/ms
# Warmup Iteration   2: 4.553 ops/ms
# Warmup Iteration   3: 5.595 ops/ms
Iteration   1: 5.678 ops/ms
Iteration   2: 5.816 ops/ms
Iteration   3: 5.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.795 ±(99.9%) 1.973 ops/ms [Average]
  (min, avg, max) = (5.678, 5.795, 5.892), stdev = 0.108
  CI (99.9%): [3.822, 7.768] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 3.786 ops/ms
# Warmup Iteration   3: 5.389 ops/ms
Iteration   1: 5.366 ops/ms
Iteration   2: 5.526 ops/ms
Iteration   3: 5.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.477 ±(99.9%) 1.770 ops/ms [Average]
  (min, avg, max) = (5.366, 5.477, 5.540), stdev = 0.097
  CI (99.9%): [3.708, 7.247] (assumes normal distribution)


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
# Warmup Iteration   1: 1.549 ops/ms
# Warmup Iteration   2: 3.645 ops/ms
# Warmup Iteration   3: 4.409 ops/ms
Iteration   1: 4.672 ops/ms
Iteration   2: 4.771 ops/ms
Iteration   3: 4.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.743 ±(99.9%) 1.133 ops/ms [Average]
  (min, avg, max) = (4.672, 4.743, 4.787), stdev = 0.062
  CI (99.9%): [3.610, 5.877] (assumes normal distribution)


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
# Warmup Iteration   1: 18.524 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 7.671 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.162 ±(99.9%) 0.011 ms/op
Iteration   1: 5.925 ±(99.9%) 0.016 ms/op
Iteration   2: 5.910 ±(99.9%) 0.008 ms/op
Iteration   3: 5.879 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.905 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (5.879, 5.905, 5.925), stdev = 0.024
  CI (99.9%): [5.475, 6.335] (assumes normal distribution)


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
# Warmup Iteration   1: 17.339 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.627 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.012 ms/op
Iteration   1: 5.537 ±(99.9%) 0.010 ms/op
Iteration   2: 5.328 ±(99.9%) 0.013 ms/op
Iteration   3: 5.410 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.425 ±(99.9%) 1.919 ms/op [Average]
  (min, avg, max) = (5.328, 5.425, 5.537), stdev = 0.105
  CI (99.9%): [3.506, 7.344] (assumes normal distribution)


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
# Warmup Iteration   1: 21.061 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 7.603 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.008 ±(99.9%) 0.013 ms/op
Iteration   1: 5.900 ±(99.9%) 0.011 ms/op
Iteration   2: 5.842 ±(99.9%) 0.009 ms/op
Iteration   3: 5.986 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.909 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (5.842, 5.909, 5.986), stdev = 0.072
  CI (99.9%): [4.594, 7.225] (assumes normal distribution)


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
# Warmup Iteration   1: 21.648 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 8.169 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.742 ±(99.9%) 0.012 ms/op
Iteration   1: 6.451 ±(99.9%) 0.020 ms/op
Iteration   2: 6.597 ±(99.9%) 0.018 ms/op
Iteration   3: 6.569 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.539 ±(99.9%) 1.411 ms/op [Average]
  (min, avg, max) = (6.451, 6.539, 6.597), stdev = 0.077
  CI (99.9%): [5.128, 7.950] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.690 ±(99.9%) 0.366 ms/op
# Warmup Iteration   2: 7.583 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.325 ±(99.9%) 0.031 ms/op
Iteration   1: 5.737 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.552 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   6.963 ms/op
                 createUser·p0.95:   7.843 ms/op
                 createUser·p0.99:   10.535 ms/op
                 createUser·p0.999:  26.625 ms/op
                 createUser·p0.9999: 28.883 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   2: 5.682 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.380 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   6.922 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  14.647 ms/op
                 createUser·p0.9999: 32.342 ms/op
                 createUser·p1.00:   33.260 ms/op

Iteration   3: 5.737 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   7.946 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  30.573 ms/op
                 createUser·p0.9999: 34.237 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167808
  mean =      5.719 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 46079 
    [ 5.000,  7.500) = 111063 
    [ 7.500, 10.000) = 8266 
    [10.000, 12.500) = 1677 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     26.942 ms/op
     p(99.9900) =     33.029 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 19.198 ±(99.9%) 0.301 ms/op
# Warmup Iteration   2: 6.219 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.705 ±(99.9%) 0.024 ms/op
Iteration   1: 5.587 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   8.126 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  16.843 ms/op
                 existUser·p0.9999: 28.532 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   2: 5.489 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   5.186 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.700 ms/op
                 existUser·p0.99:   10.602 ms/op
                 existUser·p0.999:  30.239 ms/op
                 existUser·p0.9999: 37.498 ms/op
                 existUser·p1.00:   37.880 ms/op

Iteration   3: 5.766 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   1.946 ms/op
                 existUser·p0.50:   5.292 ms/op
                 existUser·p0.90:   7.438 ms/op
                 existUser·p0.95:   9.263 ms/op
                 existUser·p0.99:   12.796 ms/op
                 existUser·p0.999:  28.623 ms/op
                 existUser·p0.9999: 31.752 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170957
  mean =      5.612 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 59017 
    [ 5.000,  7.500) = 99403 
    [ 7.500, 10.000) = 9023 
    [10.000, 12.500) = 2516 
    [12.500, 15.000) = 594 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.963 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     36.956 ms/op
     p(99.9990) =     37.833 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 19.677 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.547 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.405 ±(99.9%) 0.028 ms/op
Iteration   1: 6.157 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.589 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   7.913 ms/op
                 getUser·p0.95:   9.814 ms/op
                 getUser·p0.99:   14.696 ms/op
                 getUser·p0.999:  28.515 ms/op
                 getUser·p0.9999: 37.277 ms/op
                 getUser·p1.00:   38.207 ms/op

Iteration   2: 5.962 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.855 ms/op
                 getUser·p0.50:   5.554 ms/op
                 getUser·p0.90:   7.660 ms/op
                 getUser·p0.95:   8.946 ms/op
                 getUser·p0.99:   12.321 ms/op
                 getUser·p0.999:  28.005 ms/op
                 getUser·p0.9999: 33.554 ms/op
                 getUser·p1.00:   35.455 ms/op

Iteration   3: 6.100 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   5.677 ms/op
                 getUser·p0.90:   7.913 ms/op
                 getUser·p0.95:   9.339 ms/op
                 getUser·p0.99:   12.419 ms/op
                 getUser·p0.999:  22.162 ms/op
                 getUser·p0.9999: 31.515 ms/op
                 getUser·p1.00:   36.897 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 158151
  mean =      6.072 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 29173 
    [ 5.000,  7.500) = 110166 
    [ 7.500, 10.000) = 13117 
    [10.000, 12.500) = 3673 
    [12.500, 15.000) = 1104 
    [15.000, 17.500) = 447 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.589 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.832 ms/op
     p(95.0000) =      9.339 ms/op
     p(99.0000) =     13.369 ms/op
     p(99.9000) =     27.145 ms/op
     p(99.9900) =     33.528 ms/op
     p(99.9990) =     38.055 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 23.639 ±(99.9%) 0.424 ms/op
# Warmup Iteration   2: 8.882 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 7.548 ±(99.9%) 0.042 ms/op
Iteration   1: 7.066 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   3.514 ms/op
                 listUser·p0.50:   6.455 ms/op
                 listUser·p0.90:   9.355 ms/op
                 listUser·p0.95:   11.125 ms/op
                 listUser·p0.99:   14.860 ms/op
                 listUser·p0.999:  26.042 ms/op
                 listUser·p0.9999: 28.786 ms/op
                 listUser·p1.00:   30.802 ms/op

Iteration   2: 7.047 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   6.496 ms/op
                 listUser·p0.90:   9.044 ms/op
                 listUser·p0.95:   10.633 ms/op
                 listUser·p0.99:   14.714 ms/op
                 listUser·p0.999:  31.523 ms/op
                 listUser·p0.9999: 37.844 ms/op
                 listUser·p1.00:   38.207 ms/op

Iteration   3: 6.992 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   10.111 ms/op
                 listUser·p0.99:   13.799 ms/op
                 listUser·p0.999:  29.458 ms/op
                 listUser·p0.9999: 33.515 ms/op
                 listUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136436
  mean =      7.035 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 3267 
    [ 5.000,  7.500) = 103373 
    [ 7.500, 10.000) = 20750 
    [10.000, 12.500) = 5944 
    [12.500, 15.000) = 1955 
    [15.000, 17.500) = 659 
    [17.500, 20.000) = 171 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 66 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      6.496 ms/op
     p(90.0000) =      9.011 ms/op
     p(95.0000) =     10.617 ms/op
     p(99.0000) =     14.500 ms/op
     p(99.9000) =     28.377 ms/op
     p(99.9900) =     36.658 ms/op
     p(99.9990) =     38.136 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.305 ± 2.701  ops/ms
ClientPb.existUser                       thrpt       3   5.795 ± 1.973  ops/ms
ClientPb.getUser                         thrpt       3   5.477 ± 1.770  ops/ms
ClientPb.listUser                        thrpt       3   4.743 ± 1.133  ops/ms
ClientPb.createUser                       avgt       3   5.905 ± 0.430   ms/op
ClientPb.existUser                        avgt       3   5.425 ± 1.919   ms/op
ClientPb.getUser                          avgt       3   5.909 ± 1.315   ms/op
ClientPb.listUser                         avgt       3   6.539 ± 1.411   ms/op
ClientPb.createUser                     sample  167808   5.719 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.302           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.963           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.848           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.666           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.942           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.029           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.176           ms/op
ClientPb.existUser                      sample  170957   5.612 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.243           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.963           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.389           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.321           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.644           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.956           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.880           ms/op
ClientPb.getUser                        sample  158151   6.072 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.832           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.369           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.145           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.528           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  136436   7.035 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.617           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.500           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.377           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.658           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.207           ms/op
