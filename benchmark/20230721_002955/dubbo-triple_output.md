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
# Warmup Iteration   1: 1.933 ops/ms
# Warmup Iteration   2: 5.168 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.945 ops/ms
Iteration   2: 9.344 ops/ms
Iteration   3: 9.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.100 ±(99.9%) 3.892 ops/ms [Average]
  (min, avg, max) = (8.945, 9.100, 9.344), stdev = 0.213
  CI (99.9%): [5.209, 12.992] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.621 ops/ms
# Warmup Iteration   2: 8.916 ops/ms
# Warmup Iteration   3: 8.963 ops/ms
Iteration   1: 9.409 ops/ms
Iteration   2: 9.898 ops/ms
Iteration   3: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.631 ±(99.9%) 4.512 ops/ms [Average]
  (min, avg, max) = (9.409, 9.631, 9.898), stdev = 0.247
  CI (99.9%): [5.119, 14.143] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.988 ops/ms
# Warmup Iteration   2: 8.209 ops/ms
# Warmup Iteration   3: 8.979 ops/ms
Iteration   1: 8.960 ops/ms
Iteration   2: 9.174 ops/ms
Iteration   3: 9.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.095 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (8.960, 9.095, 9.174), stdev = 0.118
  CI (99.9%): [6.944, 11.246] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 7.181 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.886 ops/ms
Iteration   3: 7.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.799 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (7.748, 7.799, 7.886), stdev = 0.076
  CI (99.9%): [6.407, 9.190] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.071 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.005 ms/op
Iteration   1: 3.432 ±(99.9%) 0.008 ms/op
Iteration   2: 3.399 ±(99.9%) 0.006 ms/op
Iteration   3: 3.431 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.421 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.399, 3.421, 3.432), stdev = 0.019
  CI (99.9%): [3.080, 3.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.437 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.004 ms/op
Iteration   1: 3.353 ±(99.9%) 0.007 ms/op
Iteration   2: 3.300 ±(99.9%) 0.007 ms/op
Iteration   3: 3.273 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.309 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.273, 3.309, 3.353), stdev = 0.041
  CI (99.9%): [2.569, 4.048] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.427 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.004 ms/op
Iteration   1: 3.403 ±(99.9%) 0.010 ms/op
Iteration   2: 3.692 ±(99.9%) 0.005 ms/op
Iteration   3: 3.503 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.533 ±(99.9%) 2.682 ms/op [Average]
  (min, avg, max) = (3.403, 3.533, 3.692), stdev = 0.147
  CI (99.9%): [0.851, 6.215] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.647 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.007 ms/op
Iteration   1: 4.116 ±(99.9%) 0.012 ms/op
Iteration   2: 4.086 ±(99.9%) 0.010 ms/op
Iteration   3: 3.990 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.064 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (3.990, 4.064, 4.116), stdev = 0.066
  CI (99.9%): [2.855, 5.273] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.895 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.013 ms/op
Iteration   1: 3.555 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.843 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 21.954 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.505 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  20.928 ms/op
                 createUser·p0.9999: 28.569 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  19.762 ms/op
                 createUser·p0.9999: 24.565 ms/op
                 createUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274679
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10788 
    [ 2.500,  5.000) = 256191 
    [ 5.000,  7.500) = 6427 
    [ 7.500, 10.000) = 759 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     29.082 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.103 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
Iteration   1: 3.398 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  18.612 ms/op
                 existUser·p0.9999: 37.039 ms/op
                 existUser·p1.00:   38.273 ms/op

Iteration   2: 3.364 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   6.737 ms/op
                 existUser·p0.999:  21.268 ms/op
                 existUser·p0.9999: 25.886 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.404 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.917 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  9.044 ms/op
                 existUser·p0.9999: 24.145 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283072
  mean =      3.388 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7926 
    [ 2.500,  5.000) = 269370 
    [ 5.000,  7.500) = 4792 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     35.415 ms/op
     p(99.9990) =     37.990 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.244 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.010 ms/op
Iteration   1: 3.555 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  19.743 ms/op
                 getUser·p0.9999: 22.676 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   2: 3.562 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  21.823 ms/op
                 getUser·p0.9999: 30.509 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  23.298 ms/op
                 getUser·p0.9999: 26.258 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274243
  mean =      3.501 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9462 
    [ 2.500,  5.000) = 254186 
    [ 5.000,  7.500) = 9353 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.419 ms/op
     p(99.9000) =     20.341 ms/op
     p(99.9900) =     29.253 ms/op
     p(99.9990) =     31.114 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.089 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.366 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.014 ms/op
Iteration   1: 4.028 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  21.054 ms/op
                 listUser·p0.9999: 23.922 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 3.936 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   16.728 ms/op

Iteration   3: 4.064 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.928 ms/op
                 listUser·p0.999:  15.131 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239442
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 230233 
    [ 5.000,  7.500) = 6657 
    [ 7.500, 10.000) = 1611 
    [10.000, 12.500) = 377 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 197 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     25.587 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.100 ± 3.892  ops/ms
ClientPb.existUser                       thrpt       3   9.631 ± 4.512  ops/ms
ClientPb.getUser                         thrpt       3   9.095 ± 2.151  ops/ms
ClientPb.listUser                        thrpt       3   7.799 ± 1.392  ops/ms
ClientPb.createUser                       avgt       3   3.421 ± 0.340   ms/op
ClientPb.existUser                        avgt       3   3.309 ± 0.740   ms/op
ClientPb.getUser                          avgt       3   3.533 ± 2.682   ms/op
ClientPb.listUser                         avgt       3   4.064 ± 1.209   ms/op
ClientPb.createUser                     sample  274679   3.495 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.366           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.263           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  283072   3.388 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.479           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.650           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.912           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.415           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.273           ms/op
ClientPb.getUser                        sample  274243   3.501 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.939           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.419           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.341           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.253           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.228           ms/op
ClientPb.listUser                       sample  239442   4.009 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
