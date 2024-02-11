# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.024 ops/ms
# Warmup Iteration   2: 11.738 ops/ms
# Warmup Iteration   3: 11.934 ops/ms
Iteration   1: 12.175 ops/ms
Iteration   2: 12.146 ops/ms
Iteration   3: 12.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.115 ±(99.9%) 1.472 ops/ms [Average]
  (min, avg, max) = (12.023, 12.115, 12.175), stdev = 0.081
  CI (99.9%): [10.643, 13.587] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 12.459 ops/ms
# Warmup Iteration   3: 12.364 ops/ms
Iteration   1: 12.448 ops/ms
Iteration   2: 12.424 ops/ms
Iteration   3: 12.559 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.477 ±(99.9%) 1.316 ops/ms [Average]
  (min, avg, max) = (12.424, 12.477, 12.559), stdev = 0.072
  CI (99.9%): [11.161, 13.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.029 ops/ms
# Warmup Iteration   2: 11.882 ops/ms
# Warmup Iteration   3: 12.126 ops/ms
Iteration   1: 12.216 ops/ms
Iteration   2: 12.223 ops/ms
Iteration   3: 12.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.223 ±(99.9%) 0.137 ops/ms [Average]
  (min, avg, max) = (12.216, 12.223, 12.231), stdev = 0.008
  CI (99.9%): [12.086, 12.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.356 ops/ms
# Warmup Iteration   2: 10.199 ops/ms
# Warmup Iteration   3: 10.127 ops/ms
Iteration   1: 10.095 ops/ms
Iteration   2: 9.973 ops/ms
Iteration   3: 10.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.027 ±(99.9%) 1.134 ops/ms [Average]
  (min, avg, max) = (9.973, 10.027, 10.095), stdev = 0.062
  CI (99.9%): [8.893, 11.161] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.560 ±(99.9%) 0.004 ms/op
Iteration   1: 2.573 ±(99.9%) 0.005 ms/op
Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
Iteration   3: 2.568 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.560 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (2.539, 2.560, 2.573), stdev = 0.018
  CI (99.9%): [2.226, 2.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.638 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.637 ±(99.9%) 0.005 ms/op
Iteration   1: 2.598 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
Iteration   3: 2.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.562 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.531, 2.562, 2.598), stdev = 0.034
  CI (99.9%): [1.951, 3.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.735 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.657 ±(99.9%) 0.004 ms/op
Iteration   1: 2.623 ±(99.9%) 0.004 ms/op
Iteration   2: 2.665 ±(99.9%) 0.005 ms/op
Iteration   3: 2.647 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.645 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (2.623, 2.645, 2.665), stdev = 0.021
  CI (99.9%): [2.264, 3.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.175 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.007 ms/op
Iteration   1: 3.268 ±(99.9%) 0.004 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.227 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.235 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.209, 3.235, 3.268), stdev = 0.030
  CI (99.9%): [2.682, 3.788] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 2.766 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.653 ±(99.9%) 0.007 ms/op
Iteration   1: 2.667 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.269 ms/op
                 createUser·p0.95:   3.432 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  14.043 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 2.713 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   2.757 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.465 ms/op
                 createUser·p0.99:   4.193 ms/op
                 createUser·p0.999:  13.176 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 2.697 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.736 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  13.500 ms/op
                 createUser·p0.9999: 16.354 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 356188
  mean =      2.692 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 161754 
    [ 2.500,  3.750) = 186779 
    [ 3.750,  5.000) = 6188 
    [ 5.000,  6.250) = 868 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 111 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 61 
    [17.500, 18.750) = 88 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.445 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     18.395 ms/op
     p(99.9990) =     18.954 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.109 ms/op
                 existUser·p0.95:   3.228 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.140 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 2.582 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.630 ms/op
                 existUser·p0.90:   3.138 ms/op
                 existUser·p0.95:   3.305 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  13.538 ms/op
                 existUser·p0.9999: 21.365 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 2.605 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   2.646 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.326 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 17.236 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 372053
  mean =      2.577 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178832 
    [ 2.500,  5.000) = 191871 
    [ 5.000,  7.500) = 986 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.146 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      4.061 ms/op
     p(99.9000) =      7.035 ms/op
     p(99.9900) =     19.949 ms/op
     p(99.9990) =     21.547 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.621 ±(99.9%) 0.006 ms/op
Iteration   1: 2.628 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.219 ms/op
                 getUser·p0.95:   3.445 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  14.582 ms/op
                 getUser·p0.9999: 17.946 ms/op
                 getUser·p1.00:   18.481 ms/op

Iteration   2: 2.654 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.671 ms/op
                 getUser·p0.90:   3.236 ms/op
                 getUser·p0.95:   3.441 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  12.903 ms/op
                 getUser·p0.9999: 23.034 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   3: 2.635 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.224 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 15.937 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 363445
  mean =      2.639 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 167532 
    [ 2.500,  5.000) = 193902 
    [ 5.000,  7.500) = 1657 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.228 ms/op
     p(95.0000) =      3.412 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.751 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.203 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.011 ms/op
Iteration   1: 3.174 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   3.076 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.029 ms/op
                 listUser·p0.999:  13.662 ms/op
                 listUser·p0.9999: 16.511 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   2: 3.178 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  14.434 ms/op
                 listUser·p0.9999: 15.859 ms/op
                 listUser·p1.00:   16.056 ms/op

Iteration   3: 3.190 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.647 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   6.111 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 15.285 ms/op
                 listUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 301562
  mean =      3.181 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 65747 
    [ 2.500,  3.750) = 182493 
    [ 3.750,  5.000) = 42430 
    [ 5.000,  6.250) = 8493 
    [ 6.250,  7.500) = 1502 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 162 
    [13.750, 15.000) = 193 
    [15.000, 16.250) = 132 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     14.065 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     17.399 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.115 ± 1.472  ops/ms
ClientPb.existUser                       thrpt       3  12.477 ± 1.316  ops/ms
ClientPb.getUser                         thrpt       3  12.223 ± 0.137  ops/ms
ClientPb.listUser                        thrpt       3  10.027 ± 1.134  ops/ms
ClientPb.createUser                       avgt       3   2.560 ± 0.334   ms/op
ClientPb.existUser                        avgt       3   2.562 ± 0.611   ms/op
ClientPb.getUser                          avgt       3   2.645 ± 0.380   ms/op
ClientPb.listUser                         avgt       3   3.235 ± 0.553   ms/op
ClientPb.createUser                     sample  356188   2.692 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.724           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.369           ms/op
ClientPb.createUser:createUser·p0.9999  sample          18.395           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.169           ms/op
ClientPb.existUser                      sample  372053   2.577 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.605           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.061           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.035           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.949           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.594           ms/op
ClientPb.getUser                        sample  363445   2.639 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.901           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.650           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.389           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.512           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.019           ms/op
ClientPb.listUser                       sample  301562   3.181 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.084           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.038           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.065           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.024           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.498           ms/op
