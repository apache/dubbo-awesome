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
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 5.365 ops/ms
# Warmup Iteration   3: 9.523 ops/ms
Iteration   1: 10.237 ops/ms
Iteration   2: 10.293 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.316 ±(99.9%) 1.680 ops/ms [Average]
  (min, avg, max) = (10.237, 10.316, 10.417), stdev = 0.092
  CI (99.9%): [8.636, 11.995] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.269 ops/ms
# Warmup Iteration   2: 9.253 ops/ms
# Warmup Iteration   3: 10.273 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.575 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (10.533, 10.575, 10.632), stdev = 0.051
  CI (99.9%): [9.645, 11.505] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.575 ops/ms
# Warmup Iteration   2: 9.055 ops/ms
# Warmup Iteration   3: 9.693 ops/ms
Iteration   1: 10.289 ops/ms
Iteration   2: 10.470 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.382 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (10.289, 10.382, 10.470), stdev = 0.091
  CI (99.9%): [8.729, 12.035] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.269 ops/ms
# Warmup Iteration   2: 7.893 ops/ms
# Warmup Iteration   3: 8.482 ops/ms
Iteration   1: 8.358 ops/ms
Iteration   2: 8.503 ops/ms
Iteration   3: 8.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.474 ±(99.9%) 1.911 ops/ms [Average]
  (min, avg, max) = (8.358, 8.474, 8.561), stdev = 0.105
  CI (99.9%): [6.563, 10.385] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.219 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.005 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
Iteration   2: 3.262 ±(99.9%) 0.007 ms/op
Iteration   3: 3.217 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.197 ±(99.9%) 1.404 ms/op [Average]
  (min, avg, max) = (3.112, 3.197, 3.262), stdev = 0.077
  CI (99.9%): [1.793, 4.601] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.291 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.001 ms/op
Iteration   2: 3.077 ±(99.9%) 0.008 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.090 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (3.043, 3.090, 3.149), stdev = 0.054
  CI (99.9%): [2.097, 4.083] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.072 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.005 ms/op
Iteration   1: 3.141 ±(99.9%) 0.005 ms/op
Iteration   2: 3.099 ±(99.9%) 0.003 ms/op
Iteration   3: 3.037 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.092 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.037, 3.092, 3.141), stdev = 0.052
  CI (99.9%): [2.135, 4.049] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.469 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.004 ms/op
Iteration   1: 3.664 ±(99.9%) 0.009 ms/op
Iteration   2: 3.681 ±(99.9%) 0.009 ms/op
Iteration   3: 3.712 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.686 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.664, 3.686, 3.712), stdev = 0.025
  CI (99.9%): [3.238, 4.133] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.020 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.009 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  10.849 ms/op
                 createUser·p0.9999: 24.344 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.618 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  17.487 ms/op
                 createUser·p0.9999: 21.655 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  11.532 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305720
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24953 
    [ 2.500,  5.000) = 276540 
    [ 5.000,  7.500) = 3468 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     14.664 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     25.327 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.649 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.008 ms/op
Iteration   1: 3.137 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  9.306 ms/op
                 existUser·p0.9999: 20.638 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 28.248 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  13.745 ms/op
                 existUser·p0.9999: 25.264 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309309
  mean =      3.102 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17217 
    [ 2.500,  5.000) = 287217 
    [ 5.000,  7.500) = 4037 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     14.012 ms/op
     p(99.9900) =     27.117 ms/op
     p(99.9990) =     28.931 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.973 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.011 ms/op
Iteration   1: 3.131 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  17.757 ms/op
                 getUser·p0.9999: 20.047 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  10.150 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   24.412 ms/op

Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.878 ms/op
                 getUser·p0.999:  10.454 ms/op
                 getUser·p0.9999: 18.514 ms/op
                 getUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300580
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11968 
    [ 2.500,  5.000) = 282716 
    [ 5.000,  7.500) = 5088 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     22.280 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.883 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.202 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.012 ms/op
Iteration   1: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.746 ms/op
                 listUser·p0.9999: 18.888 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 3.813 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.047 ms/op
                 listUser·p0.999:  14.454 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   3: 3.716 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.894 ms/op
                 listUser·p0.9999: 19.157 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255582
  mean =      3.751 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 248318 
    [ 5.000,  7.500) = 5457 
    [ 7.500, 10.000) = 1108 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     14.654 ms/op
     p(99.9900) =     18.528 ms/op
     p(99.9990) =     19.854 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.316 ± 1.680  ops/ms
ClientPb.existUser                       thrpt       3  10.575 ± 0.930  ops/ms
ClientPb.getUser                         thrpt       3  10.382 ± 1.653  ops/ms
ClientPb.listUser                        thrpt       3   8.474 ± 1.911  ops/ms
ClientPb.createUser                       avgt       3   3.197 ± 1.404   ms/op
ClientPb.existUser                        avgt       3   3.090 ± 0.993   ms/op
ClientPb.getUser                          avgt       3   3.092 ± 0.957   ms/op
ClientPb.listUser                         avgt       3   3.686 ± 0.447   ms/op
ClientPb.createUser                     sample  305720   3.137 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.618           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.235           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.664           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.249           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.395           ms/op
ClientPb.existUser                      sample  309309   3.102 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.860           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.408           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.399           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.012           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.327           ms/op
ClientPb.getUser                        sample  300580   3.192 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.253           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.280           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.412           ms/op
ClientPb.listUser                       sample  255582   3.751 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.750           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.654           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.528           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.808           ms/op
