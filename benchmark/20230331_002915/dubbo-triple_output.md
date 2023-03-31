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
# Warmup Iteration   1: 1.035 ops/ms
# Warmup Iteration   2: 2.276 ops/ms
# Warmup Iteration   3: 4.516 ops/ms
Iteration   1: 4.880 ops/ms
Iteration   2: 5.002 ops/ms
Iteration   3: 5.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.070 ±(99.9%) 4.229 ops/ms [Average]
  (min, avg, max) = (4.880, 5.070, 5.328), stdev = 0.232
  CI (99.9%): [0.841, 9.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.466 ops/ms
# Warmup Iteration   2: 4.532 ops/ms
# Warmup Iteration   3: 5.560 ops/ms
Iteration   1: 5.452 ops/ms
Iteration   2: 5.376 ops/ms
Iteration   3: 5.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.451 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (5.376, 5.451, 5.526), stdev = 0.075
  CI (99.9%): [4.083, 6.820] (assumes normal distribution)


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
# Warmup Iteration   1: 1.251 ops/ms
# Warmup Iteration   2: 3.611 ops/ms
# Warmup Iteration   3: 5.083 ops/ms
Iteration   1: 5.157 ops/ms
Iteration   2: 5.218 ops/ms
Iteration   3: 5.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.257 ±(99.9%) 2.267 ops/ms [Average]
  (min, avg, max) = (5.157, 5.257, 5.396), stdev = 0.124
  CI (99.9%): [2.990, 7.524] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.382 ops/ms
# Warmup Iteration   2: 3.689 ops/ms
# Warmup Iteration   3: 4.326 ops/ms
Iteration   1: 4.607 ops/ms
Iteration   2: 4.636 ops/ms
Iteration   3: 4.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.640 ±(99.9%) 0.641 ops/ms [Average]
  (min, avg, max) = (4.607, 4.640, 4.677), stdev = 0.035
  CI (99.9%): [4.000, 5.281] (assumes normal distribution)


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
# Warmup Iteration   1: 20.122 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 7.573 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.399 ±(99.9%) 0.014 ms/op
Iteration   1: 6.091 ±(99.9%) 0.019 ms/op
Iteration   2: 6.043 ±(99.9%) 0.014 ms/op
Iteration   3: 6.050 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.061 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (6.043, 6.061, 6.091), stdev = 0.026
  CI (99.9%): [5.596, 6.527] (assumes normal distribution)


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
# Warmup Iteration   1: 20.335 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.017 ±(99.9%) 0.007 ms/op
Iteration   1: 5.787 ±(99.9%) 0.009 ms/op
Iteration   2: 5.715 ±(99.9%) 0.015 ms/op
Iteration   3: 5.908 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.803 ±(99.9%) 1.779 ms/op [Average]
  (min, avg, max) = (5.715, 5.803, 5.908), stdev = 0.097
  CI (99.9%): [4.024, 7.582] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.716 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 7.593 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.115 ±(99.9%) 0.012 ms/op
Iteration   1: 6.175 ±(99.9%) 0.011 ms/op
Iteration   2: 5.974 ±(99.9%) 0.018 ms/op
Iteration   3: 5.973 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.041 ±(99.9%) 2.127 ms/op [Average]
  (min, avg, max) = (5.973, 6.041, 6.175), stdev = 0.117
  CI (99.9%): [3.914, 8.168] (assumes normal distribution)


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
# Warmup Iteration   1: 24.732 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 9.735 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.651 ±(99.9%) 0.017 ms/op
Iteration   1: 7.287 ±(99.9%) 0.013 ms/op
Iteration   2: 7.241 ±(99.9%) 0.015 ms/op
Iteration   3: 7.512 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.346 ±(99.9%) 2.644 ms/op [Average]
  (min, avg, max) = (7.241, 7.346, 7.512), stdev = 0.145
  CI (99.9%): [4.702, 9.991] (assumes normal distribution)


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
# Warmup Iteration   1: 20.497 ±(99.9%) 0.360 ms/op
# Warmup Iteration   2: 8.316 ±(99.9%) 0.060 ms/op
# Warmup Iteration   3: 6.586 ±(99.9%) 0.035 ms/op
Iteration   1: 6.315 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   5.833 ms/op
                 createUser·p0.90:   8.208 ms/op
                 createUser·p0.95:   9.798 ms/op
                 createUser·p0.99:   13.631 ms/op
                 createUser·p0.999:  23.134 ms/op
                 createUser·p0.9999: 34.328 ms/op
                 createUser·p1.00:   35.258 ms/op

Iteration   2: 5.965 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   5.702 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.045 ms/op
                 createUser·p0.99:   10.445 ms/op
                 createUser·p0.999:  29.572 ms/op
                 createUser·p0.9999: 32.991 ms/op
                 createUser·p1.00:   33.489 ms/op

Iteration   3: 5.883 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   7.873 ms/op
                 createUser·p0.99:   10.437 ms/op
                 createUser·p0.999:  27.972 ms/op
                 createUser·p0.9999: 33.805 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 158627
  mean =      6.049 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 19675 
    [ 5.000,  7.500) = 123691 
    [ 7.500, 10.000) = 11575 
    [10.000, 12.500) = 2552 
    [12.500, 15.000) = 584 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 44 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      5.710 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     27.549 ms/op
     p(99.9900) =     33.891 ms/op
     p(99.9990) =     35.855 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.297 ±(99.9%) 0.294 ms/op
# Warmup Iteration   2: 7.208 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.865 ±(99.9%) 0.021 ms/op
Iteration   1: 5.734 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   5.407 ms/op
                 existUser·p0.90:   7.102 ms/op
                 existUser·p0.95:   8.167 ms/op
                 existUser·p0.99:   10.666 ms/op
                 existUser·p0.999:  16.335 ms/op
                 existUser·p0.9999: 25.467 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 5.713 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.515 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.097 ms/op
                 existUser·p0.95:   8.266 ms/op
                 existUser·p0.99:   11.747 ms/op
                 existUser·p0.999:  26.348 ms/op
                 existUser·p0.9999: 32.342 ms/op
                 existUser·p1.00:   32.670 ms/op

Iteration   3: 5.903 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.408 ms/op
                 existUser·p0.50:   5.521 ms/op
                 existUser·p0.90:   7.414 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   11.207 ms/op
                 existUser·p0.999:  29.486 ms/op
                 existUser·p0.9999: 33.233 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 165893
  mean =      5.782 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 34338 
    [ 5.000,  7.500) = 117967 
    [ 7.500, 10.000) = 10500 
    [10.000, 12.500) = 2228 
    [12.500, 15.000) = 466 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.408 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      7.209 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.239 ms/op
     p(99.9000) =     23.728 ms/op
     p(99.9900) =     32.355 ms/op
     p(99.9990) =     33.667 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 21.094 ±(99.9%) 0.357 ms/op
# Warmup Iteration   2: 7.853 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 6.065 ±(99.9%) 0.023 ms/op
Iteration   1: 6.099 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   7.930 ms/op
                 getUser·p0.95:   9.454 ms/op
                 getUser·p0.99:   12.452 ms/op
                 getUser·p0.999:  30.361 ms/op
                 getUser·p0.9999: 34.737 ms/op
                 getUser·p1.00:   38.207 ms/op

Iteration   2: 6.297 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.560 ms/op
                 getUser·p0.50:   5.751 ms/op
                 getUser·p0.90:   8.290 ms/op
                 getUser·p0.95:   9.841 ms/op
                 getUser·p0.99:   13.752 ms/op
                 getUser·p0.999:  27.417 ms/op
                 getUser·p0.9999: 30.373 ms/op
                 getUser·p1.00:   31.883 ms/op

Iteration   3: 6.075 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.228 ms/op
                 getUser·p0.50:   5.718 ms/op
                 getUser·p0.90:   7.766 ms/op
                 getUser·p0.95:   8.880 ms/op
                 getUser·p0.99:   11.646 ms/op
                 getUser·p0.999:  15.154 ms/op
                 getUser·p0.9999: 31.866 ms/op
                 getUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155833
  mean =      6.155 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 21387 
    [ 5.000,  7.500) = 114645 
    [ 7.500, 10.000) = 14399 
    [10.000, 12.500) = 3707 
    [12.500, 15.000) = 1059 
    [15.000, 17.500) = 226 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      5.702 ms/op
     p(90.0000) =      7.963 ms/op
     p(95.0000) =      9.404 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     27.268 ms/op
     p(99.9900) =     33.093 ms/op
     p(99.9990) =     36.963 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 20.625 ±(99.9%) 0.377 ms/op
# Warmup Iteration   2: 9.164 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 7.261 ±(99.9%) 0.033 ms/op
Iteration   1: 7.018 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.355 ms/op
                 listUser·p0.50:   6.636 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.716 ms/op
                 listUser·p0.99:   13.171 ms/op
                 listUser·p0.999:  27.656 ms/op
                 listUser·p0.9999: 31.368 ms/op
                 listUser·p1.00:   32.244 ms/op

Iteration   2: 6.863 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.391 ms/op
                 listUser·p0.50:   6.439 ms/op
                 listUser·p0.90:   8.249 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  27.165 ms/op
                 listUser·p0.9999: 29.766 ms/op
                 listUser·p1.00:   30.441 ms/op

Iteration   3: 6.859 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   6.537 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.026 ms/op
                 listUser·p0.999:  30.596 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138810
  mean =      6.913 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1872 
    [ 5.000,  7.500) = 110990 
    [ 7.500, 10.000) = 20669 
    [10.000, 12.500) = 3661 
    [12.500, 15.000) = 939 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.896 ms/op
     p(50.0000) =      6.537 ms/op
     p(90.0000) =      8.266 ms/op
     p(95.0000) =      9.461 ms/op
     p(99.0000) =     12.812 ms/op
     p(99.9000) =     27.865 ms/op
     p(99.9900) =     32.333 ms/op
     p(99.9990) =     33.791 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.070 ± 4.229  ops/ms
ClientPb.existUser                       thrpt       3   5.451 ± 1.368  ops/ms
ClientPb.getUser                         thrpt       3   5.257 ± 2.267  ops/ms
ClientPb.listUser                        thrpt       3   4.640 ± 0.641  ops/ms
ClientPb.createUser                       avgt       3   6.061 ± 0.465   ms/op
ClientPb.existUser                        avgt       3   5.803 ± 1.779   ms/op
ClientPb.getUser                          avgt       3   6.041 ± 2.127   ms/op
ClientPb.listUser                         avgt       3   7.346 ± 2.644   ms/op
ClientPb.createUser                     sample  158627   6.049 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.536           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.583           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.549           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.891           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  165893   5.782 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.408           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.209           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.315           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.239           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.728           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.355           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  155833   6.155 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.646           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.963           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.404           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.730           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.093           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.207           ms/op
ClientPb.listUser                       sample  138810   6.913 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.537           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.461           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.812           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.865           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.333           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
