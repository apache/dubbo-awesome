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
# Warmup Iteration   1: 1.163 ops/ms
# Warmup Iteration   2: 2.563 ops/ms
# Warmup Iteration   3: 5.710 ops/ms
Iteration   1: 6.060 ops/ms
Iteration   2: 6.175 ops/ms
Iteration   3: 6.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.204 ±(99.9%) 2.929 ops/ms [Average]
  (min, avg, max) = (6.060, 6.204, 6.377), stdev = 0.161
  CI (99.9%): [3.275, 9.133] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.655 ops/ms
# Warmup Iteration   2: 4.793 ops/ms
# Warmup Iteration   3: 6.417 ops/ms
Iteration   1: 6.750 ops/ms
Iteration   2: 7.126 ops/ms
Iteration   3: 6.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.846 ±(99.9%) 4.501 ops/ms [Average]
  (min, avg, max) = (6.662, 6.846, 7.126), stdev = 0.247
  CI (99.9%): [2.345, 11.347] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.906 ops/ms
# Warmup Iteration   2: 5.561 ops/ms
# Warmup Iteration   3: 6.256 ops/ms
Iteration   1: 6.291 ops/ms
Iteration   2: 6.508 ops/ms
Iteration   3: 6.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.408 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (6.291, 6.408, 6.508), stdev = 0.110
  CI (99.9%): [4.407, 8.410] (assumes normal distribution)


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
# Warmup Iteration   1: 1.772 ops/ms
# Warmup Iteration   2: 4.752 ops/ms
# Warmup Iteration   3: 5.414 ops/ms
Iteration   1: 5.478 ops/ms
Iteration   2: 5.212 ops/ms
Iteration   3: 5.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.437 ±(99.9%) 3.775 ops/ms [Average]
  (min, avg, max) = (5.212, 5.437, 5.620), stdev = 0.207
  CI (99.9%): [1.662, 9.212] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.197 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.992 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.389 ±(99.9%) 0.010 ms/op
Iteration   1: 4.826 ±(99.9%) 0.017 ms/op
Iteration   2: 5.171 ±(99.9%) 0.016 ms/op
Iteration   3: 5.179 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.059 ±(99.9%) 3.677 ms/op [Average]
  (min, avg, max) = (4.826, 5.059, 5.179), stdev = 0.202
  CI (99.9%): [1.382, 8.736] (assumes normal distribution)


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
# Warmup Iteration   1: 15.635 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.323 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.072 ±(99.9%) 0.009 ms/op
Iteration   1: 4.916 ±(99.9%) 0.012 ms/op
Iteration   2: 4.856 ±(99.9%) 0.009 ms/op
Iteration   3: 4.799 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.857 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (4.799, 4.857, 4.916), stdev = 0.058
  CI (99.9%): [3.792, 5.922] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.443 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.490 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.987 ±(99.9%) 0.013 ms/op
Iteration   1: 4.894 ±(99.9%) 0.016 ms/op
Iteration   2: 4.905 ±(99.9%) 0.018 ms/op
Iteration   3: 4.919 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.906 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (4.894, 4.906, 4.919), stdev = 0.013
  CI (99.9%): [4.670, 5.143] (assumes normal distribution)


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
# Warmup Iteration   1: 17.807 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.503 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.534 ±(99.9%) 0.016 ms/op
Iteration   1: 5.680 ±(99.9%) 0.009 ms/op
Iteration   2: 5.464 ±(99.9%) 0.022 ms/op
Iteration   3: 5.745 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.630 ±(99.9%) 2.689 ms/op [Average]
  (min, avg, max) = (5.464, 5.630, 5.745), stdev = 0.147
  CI (99.9%): [2.941, 8.318] (assumes normal distribution)


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
# Warmup Iteration   1: 15.435 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 6.216 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.354 ±(99.9%) 0.019 ms/op
Iteration   1: 5.076 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   6.119 ms/op
                 createUser·p0.95:   6.791 ms/op
                 createUser·p0.99:   9.290 ms/op
                 createUser·p0.999:  21.334 ms/op
                 createUser·p0.9999: 25.025 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 5.138 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.152 ms/op
                 createUser·p0.95:   6.595 ms/op
                 createUser·p0.99:   8.377 ms/op
                 createUser·p0.999:  24.175 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   3: 5.034 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   4.858 ms/op
                 createUser·p0.90:   5.964 ms/op
                 createUser·p0.95:   6.447 ms/op
                 createUser·p0.99:   8.258 ms/op
                 createUser·p0.999:  23.854 ms/op
                 createUser·p0.9999: 29.152 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188737
  mean =      5.082 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 106404 
    [ 5.000,  7.500) = 77648 
    [ 7.500, 10.000) = 3530 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 90 

  Percentiles, ms/op:
      p(0.0000) =      1.591 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     28.222 ms/op
     p(99.9990) =     29.477 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 15.308 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.507 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.794 ±(99.9%) 0.016 ms/op
Iteration   1: 4.503 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   6.062 ms/op
                 existUser·p0.99:   8.278 ms/op
                 existUser·p0.999:  15.139 ms/op
                 existUser·p0.9999: 22.888 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   2: 4.398 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.780 ms/op
                 existUser·p0.50:   4.182 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.710 ms/op
                 existUser·p0.999:  11.163 ms/op
                 existUser·p0.9999: 25.484 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   3: 4.428 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   5.464 ms/op
                 existUser·p0.95:   6.054 ms/op
                 existUser·p0.99:   8.004 ms/op
                 existUser·p0.999:  15.233 ms/op
                 existUser·p0.9999: 35.113 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 216045
  mean =      4.443 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 82 
    [ 2.500,  5.000) = 186036 
    [ 5.000,  7.500) = 26571 
    [ 7.500, 10.000) = 2600 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      4.227 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     26.758 ms/op
     p(99.9990) =     35.565 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 11.839 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 5.337 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.939 ±(99.9%) 0.015 ms/op
Iteration   1: 4.805 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.694 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.767 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   10.289 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   2: 4.602 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  18.579 ms/op
                 getUser·p0.9999: 25.568 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   3: 4.761 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.146 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.620 ms/op
                 getUser·p0.95:   6.865 ms/op
                 getUser·p0.99:   9.011 ms/op
                 getUser·p0.999:  15.254 ms/op
                 getUser·p0.9999: 29.000 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 203166
  mean =      4.721 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 161446 
    [ 5.000,  7.500) = 36526 
    [ 7.500, 10.000) = 3921 
    [10.000, 12.500) = 663 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     27.262 ms/op
     p(99.9990) =     29.779 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 17.292 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.391 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.661 ±(99.9%) 0.019 ms/op
Iteration   1: 5.095 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   8.819 ms/op
                 listUser·p0.999:  20.397 ms/op
                 listUser·p0.9999: 22.929 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 5.439 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   5.243 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   9.757 ms/op
                 listUser·p0.999:  27.312 ms/op
                 listUser·p0.9999: 30.966 ms/op
                 listUser·p1.00:   32.080 ms/op

Iteration   3: 5.223 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.900 ms/op
                 listUser·p0.50:   5.030 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.944 ms/op
                 listUser·p0.999:  19.782 ms/op
                 listUser·p0.9999: 21.745 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 182826
  mean =      5.249 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 84610 
    [ 5.000,  7.500) = 93714 
    [ 7.500, 10.000) = 3309 
    [10.000, 12.500) = 640 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.504 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     29.622 ms/op
     p(99.9990) =     31.483 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.204 ± 2.929  ops/ms
ClientPb.existUser                       thrpt       3   6.846 ± 4.501  ops/ms
ClientPb.getUser                         thrpt       3   6.408 ± 2.001  ops/ms
ClientPb.listUser                        thrpt       3   5.437 ± 3.775  ops/ms
ClientPb.createUser                       avgt       3   5.059 ± 3.677   ms/op
ClientPb.existUser                        avgt       3   4.857 ± 1.065   ms/op
ClientPb.getUser                          avgt       3   4.906 ± 0.236   ms/op
ClientPb.listUser                         avgt       3   5.630 ± 2.689   ms/op
ClientPb.createUser                     sample  188737   5.082 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.591           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.874           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.595           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.716           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.265           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.884           ms/op
ClientPb.existUser                      sample  216045   4.443 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.780           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.036           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.758           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.652           ms/op
ClientPb.getUser                        sample  203166   4.721 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.694           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.110           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.727           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.262           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  182826   5.249 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.097           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.349           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.622           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.080           ms/op
