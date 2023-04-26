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
# Warmup Iteration   1: 1.037 ops/ms
# Warmup Iteration   2: 2.376 ops/ms
# Warmup Iteration   3: 5.538 ops/ms
Iteration   1: 5.761 ops/ms
Iteration   2: 6.053 ops/ms
Iteration   3: 5.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.920 ±(99.9%) 2.693 ops/ms [Average]
  (min, avg, max) = (5.761, 5.920, 6.053), stdev = 0.148
  CI (99.9%): [3.227, 8.613] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 5.290 ops/ms
# Warmup Iteration   3: 6.234 ops/ms
Iteration   1: 6.536 ops/ms
Iteration   2: 6.350 ops/ms
Iteration   3: 6.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.382 ±(99.9%) 2.568 ops/ms [Average]
  (min, avg, max) = (6.260, 6.382, 6.536), stdev = 0.141
  CI (99.9%): [3.814, 8.949] (assumes normal distribution)


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
# Warmup Iteration   1: 1.518 ops/ms
# Warmup Iteration   2: 4.738 ops/ms
# Warmup Iteration   3: 5.741 ops/ms
Iteration   1: 5.988 ops/ms
Iteration   2: 5.972 ops/ms
Iteration   3: 5.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.973 ±(99.9%) 0.264 ops/ms [Average]
  (min, avg, max) = (5.960, 5.973, 5.988), stdev = 0.014
  CI (99.9%): [5.710, 6.237] (assumes normal distribution)


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
# Warmup Iteration   1: 1.616 ops/ms
# Warmup Iteration   2: 4.205 ops/ms
# Warmup Iteration   3: 5.369 ops/ms
Iteration   1: 5.197 ops/ms
Iteration   2: 5.424 ops/ms
Iteration   3: 5.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.338 ±(99.9%) 2.250 ops/ms [Average]
  (min, avg, max) = (5.197, 5.338, 5.424), stdev = 0.123
  CI (99.9%): [3.088, 7.588] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 19.366 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.917 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.561 ±(99.9%) 0.010 ms/op
Iteration   1: 5.147 ±(99.9%) 0.011 ms/op
Iteration   2: 5.132 ±(99.9%) 0.016 ms/op
Iteration   3: 5.127 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.135 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (5.127, 5.135, 5.147), stdev = 0.011
  CI (99.9%): [4.942, 5.329] (assumes normal distribution)


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
# Warmup Iteration   1: 16.356 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.546 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.945 ±(99.9%) 0.009 ms/op
Iteration   1: 4.930 ±(99.9%) 0.009 ms/op
Iteration   2: 5.054 ±(99.9%) 0.008 ms/op
Iteration   3: 5.007 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.997 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (4.930, 4.997, 5.054), stdev = 0.063
  CI (99.9%): [3.855, 6.139] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.697 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.581 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.491 ±(99.9%) 0.012 ms/op
Iteration   1: 5.815 ±(99.9%) 0.011 ms/op
Iteration   2: 5.401 ±(99.9%) 0.012 ms/op
Iteration   3: 5.301 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.506 ±(99.9%) 4.977 ms/op [Average]
  (min, avg, max) = (5.301, 5.506, 5.815), stdev = 0.273
  CI (99.9%): [0.528, 10.483] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.145 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.100 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.998 ±(99.9%) 0.018 ms/op
Iteration   1: 6.131 ±(99.9%) 0.018 ms/op
Iteration   2: 6.090 ±(99.9%) 0.013 ms/op
Iteration   3: 5.983 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.068 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (5.983, 6.068, 6.131), stdev = 0.076
  CI (99.9%): [4.673, 7.464] (assumes normal distribution)


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
# Warmup Iteration   1: 16.595 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 6.209 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.832 ±(99.9%) 0.025 ms/op
Iteration   1: 5.354 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.009 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.480 ms/op
                 createUser·p0.95:   7.553 ms/op
                 createUser·p0.99:   10.387 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 25.565 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 5.415 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.013 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  25.328 ms/op
                 createUser·p0.9999: 28.249 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 5.127 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.544 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   6.119 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   9.377 ms/op
                 createUser·p0.999:  26.652 ms/op
                 createUser·p0.9999: 30.900 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181184
  mean =      5.296 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 90330 
    [ 5.000,  7.500) = 82720 
    [ 7.500, 10.000) = 6120 
    [10.000, 12.500) = 1347 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     22.434 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     31.437 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 16.049 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.783 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.328 ±(99.9%) 0.019 ms/op
Iteration   1: 5.046 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.933 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.136 ms/op
                 existUser·p0.95:   6.971 ms/op
                 existUser·p0.99:   9.798 ms/op
                 existUser·p0.999:  22.499 ms/op
                 existUser·p0.9999: 28.363 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   2: 4.981 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.028 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   6.250 ms/op
                 existUser·p0.95:   7.307 ms/op
                 existUser·p0.99:   9.519 ms/op
                 existUser·p0.999:  21.611 ms/op
                 existUser·p0.9999: 30.048 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 5.045 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.290 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.300 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  25.534 ms/op
                 existUser·p0.9999: 32.515 ms/op
                 existUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 191030
  mean =      5.024 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 124060 
    [ 5.000,  7.500) = 58877 
    [ 7.500, 10.000) = 6555 
    [10.000, 12.500) = 1034 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     22.511 ms/op
     p(99.9900) =     31.768 ms/op
     p(99.9990) =     32.991 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 16.810 ±(99.9%) 0.346 ms/op
# Warmup Iteration   2: 6.066 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.499 ±(99.9%) 0.021 ms/op
Iteration   1: 5.319 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.712 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   8.045 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  24.443 ms/op
                 getUser·p0.9999: 52.100 ms/op
                 getUser·p1.00:   54.526 ms/op

Iteration   2: 5.714 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   2.642 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   7.807 ms/op
                 getUser·p0.95:   9.306 ms/op
                 getUser·p0.99:   14.107 ms/op
                 getUser·p0.999:  30.048 ms/op
                 getUser·p0.9999: 40.567 ms/op
                 getUser·p1.00:   41.288 ms/op

Iteration   3: 5.208 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   4.850 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.840 ms/op
                 getUser·p0.99:   10.387 ms/op
                 getUser·p0.999:  14.395 ms/op
                 getUser·p0.9999: 27.951 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177597
  mean =      5.405 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 96489 
    [ 5.000, 10.000) = 77233 
    [10.000, 15.000) = 3249 
    [15.000, 20.000) = 335 
    [20.000, 25.000) = 90 
    [25.000, 30.000) = 107 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.806 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     26.293 ms/op
     p(99.9900) =     49.299 ms/op
     p(99.9990) =     54.526 ms/op
     p(99.9999) =     54.526 ms/op
    p(100.0000) =     54.526 ms/op


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
# Warmup Iteration   1: 20.817 ±(99.9%) 0.353 ms/op
# Warmup Iteration   2: 8.807 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.563 ±(99.9%) 0.030 ms/op
Iteration   1: 6.573 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   8.798 ms/op
                 listUser·p0.95:   10.207 ms/op
                 listUser·p0.99:   13.828 ms/op
                 listUser·p0.999:  23.921 ms/op
                 listUser·p0.9999: 27.310 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 6.481 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   6.021 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   13.410 ms/op
                 listUser·p0.999:  27.820 ms/op
                 listUser·p0.9999: 32.416 ms/op
                 listUser·p1.00:   33.325 ms/op

Iteration   3: 6.178 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   8.249 ms/op
                 listUser·p0.95:   9.212 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  24.793 ms/op
                 listUser·p0.9999: 31.162 ms/op
                 listUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149825
  mean =      6.406 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 8812 
    [ 5.000,  7.500) = 117912 
    [ 7.500, 10.000) = 16534 
    [10.000, 12.500) = 4706 
    [12.500, 15.000) = 1234 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      5.882 ms/op
     p(90.0000) =      8.405 ms/op
     p(95.0000) =      9.748 ms/op
     p(99.0000) =     13.074 ms/op
     p(99.9000) =     25.630 ms/op
     p(99.9900) =     31.164 ms/op
     p(99.9990) =     32.999 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.920 ± 2.693  ops/ms
ClientPb.existUser                       thrpt       3   6.382 ± 2.568  ops/ms
ClientPb.getUser                         thrpt       3   5.973 ± 0.264  ops/ms
ClientPb.listUser                        thrpt       3   5.338 ± 2.250  ops/ms
ClientPb.createUser                       avgt       3   5.135 ± 0.194   ms/op
ClientPb.existUser                        avgt       3   4.997 ± 1.142   ms/op
ClientPb.getUser                          avgt       3   5.506 ± 4.977   ms/op
ClientPb.listUser                         avgt       3   6.068 ± 1.395   ms/op
ClientPb.createUser                     sample  181184   5.296 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.009           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.256           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.434           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.360           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.490           ms/op
ClientPb.existUser                      sample  191030   5.024 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.933           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.702           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.683           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.511           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.768           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  177597   5.405 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.806           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.665           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.293           ms/op
ClientPb.getUser:getUser·p0.9999        sample          49.299           ms/op
ClientPb.getUser:getUser·p1.00          sample          54.526           ms/op
ClientPb.listUser                       sample  149825   6.406 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.260           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.882           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.405           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.748           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.074           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.630           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.164           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.325           ms/op
