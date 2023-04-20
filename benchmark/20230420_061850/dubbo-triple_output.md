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
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 5.526 ops/ms
# Warmup Iteration   3: 8.557 ops/ms
Iteration   1: 9.187 ops/ms
Iteration   2: 9.473 ops/ms
Iteration   3: 9.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.233 ±(99.9%) 4.036 ops/ms [Average]
  (min, avg, max) = (9.038, 9.233, 9.473), stdev = 0.221
  CI (99.9%): [5.197, 13.269] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.575 ops/ms
# Warmup Iteration   2: 8.279 ops/ms
# Warmup Iteration   3: 9.417 ops/ms
Iteration   1: 9.992 ops/ms
Iteration   2: 9.579 ops/ms
Iteration   3: 9.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.792 ±(99.9%) 3.776 ops/ms [Average]
  (min, avg, max) = (9.579, 9.792, 9.992), stdev = 0.207
  CI (99.9%): [6.016, 13.568] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ops/ms
# Warmup Iteration   2: 7.890 ops/ms
# Warmup Iteration   3: 9.468 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.483 ops/ms
Iteration   3: 9.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.361 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (9.291, 9.361, 9.483), stdev = 0.106
  CI (99.9%): [7.433, 11.290] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.848 ops/ms
# Warmup Iteration   2: 7.245 ops/ms
# Warmup Iteration   3: 7.801 ops/ms
Iteration   1: 7.625 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.029 ±(99.9%) 6.409 ops/ms [Average]
  (min, avg, max) = (7.625, 8.029, 8.262), stdev = 0.351
  CI (99.9%): [1.620, 14.438] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.051 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.008 ms/op
Iteration   1: 3.466 ±(99.9%) 0.008 ms/op
Iteration   2: 3.501 ±(99.9%) 0.009 ms/op
Iteration   3: 3.291 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 2.056 ms/op [Average]
  (min, avg, max) = (3.291, 3.419, 3.501), stdev = 0.113
  CI (99.9%): [1.364, 5.475] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.215 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.008 ms/op
Iteration   1: 3.233 ±(99.9%) 0.008 ms/op
Iteration   2: 3.208 ±(99.9%) 0.006 ms/op
Iteration   3: 3.293 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.244 ±(99.9%) 0.797 ms/op [Average]
  (min, avg, max) = (3.208, 3.244, 3.293), stdev = 0.044
  CI (99.9%): [2.447, 4.042] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.873 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.003 ms/op
Iteration   1: 3.514 ±(99.9%) 0.005 ms/op
Iteration   2: 3.427 ±(99.9%) 0.007 ms/op
Iteration   3: 3.336 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.425 ±(99.9%) 1.622 ms/op [Average]
  (min, avg, max) = (3.336, 3.425, 3.514), stdev = 0.089
  CI (99.9%): [1.803, 5.047] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.597 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.009 ms/op
Iteration   1: 3.915 ±(99.9%) 0.010 ms/op
Iteration   2: 3.965 ±(99.9%) 0.005 ms/op
Iteration   3: 3.931 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.937 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.915, 3.937, 3.965), stdev = 0.025
  CI (99.9%): [3.474, 4.400] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.894 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.011 ms/op
Iteration   1: 3.364 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  20.944 ms/op
                 createUser·p0.9999: 24.559 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.362 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  23.839 ms/op
                 createUser·p0.9999: 27.474 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.927 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.983 ms/op
                 createUser·p0.999:  19.617 ms/op
                 createUser·p0.9999: 26.867 ms/op
                 createUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281081
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10888 
    [ 2.500,  5.000) = 263442 
    [ 5.000,  7.500) = 5654 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 116 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     28.086 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.950 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  9.568 ms/op
                 existUser·p0.9999: 23.666 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.366 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  22.906 ms/op
                 existUser·p0.9999: 30.081 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.756 ms/op
                 existUser·p0.999:  18.050 ms/op
                 existUser·p0.9999: 30.745 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286773
  mean =      3.344 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13117 
    [ 2.500,  5.000) = 267746 
    [ 5.000,  7.500) = 4804 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     29.807 ms/op
     p(99.9990) =     31.363 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.282 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.011 ms/op
Iteration   1: 3.557 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  21.040 ms/op
                 getUser·p0.9999: 22.971 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.583 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  16.695 ms/op
                 getUser·p0.9999: 24.971 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  21.014 ms/op
                 getUser·p0.9999: 26.708 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273985
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11673 
    [ 2.500,  5.000) = 253078 
    [ 5.000,  7.500) = 7884 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.532 ms/op
     p(99.9900) =     25.566 ms/op
     p(99.9990) =     27.289 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 9.493 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.228 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.014 ms/op
Iteration   1: 4.084 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  20.425 ms/op
                 listUser·p0.9999: 26.651 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   2: 4.073 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.526 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 16.377 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.983 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.168 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237015
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 228234 
    [ 5.000,  7.500) = 6185 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     25.667 ms/op
     p(99.9990) =     27.456 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.233 ± 4.036  ops/ms
ClientPb.existUser                       thrpt       3   9.792 ± 3.776  ops/ms
ClientPb.getUser                         thrpt       3   9.361 ± 1.928  ops/ms
ClientPb.listUser                        thrpt       3   8.029 ± 6.409  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 2.056   ms/op
ClientPb.existUser                        avgt       3   3.244 ± 0.797   ms/op
ClientPb.getUser                          avgt       3   3.425 ± 1.622   ms/op
ClientPb.listUser                         avgt       3   3.937 ± 0.463   ms/op
ClientPb.createUser                     sample  281081   3.414 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.927           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.792           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.694           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  286773   3.344 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.795           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.807           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.425           ms/op
ClientPb.getUser                        sample  273985   3.505 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.990           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.532           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.623           ms/op
ClientPb.listUser                       sample  237015   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.333           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.727           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.667           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
