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
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 6.447 ops/ms
# Warmup Iteration   3: 9.250 ops/ms
Iteration   1: 9.656 ops/ms
Iteration   2: 10.029 ops/ms
Iteration   3: 9.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.872 ±(99.9%) 3.526 ops/ms [Average]
  (min, avg, max) = (9.656, 9.872, 10.029), stdev = 0.193
  CI (99.9%): [6.346, 13.399] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ops/ms
# Warmup Iteration   2: 9.572 ops/ms
# Warmup Iteration   3: 9.698 ops/ms
Iteration   1: 10.217 ops/ms
Iteration   2: 9.942 ops/ms
Iteration   3: 9.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.047 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (9.942, 10.047, 10.217), stdev = 0.149
  CI (99.9%): [7.331, 12.762] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.091 ops/ms
Iteration   3: 10.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.238 ±(99.9%) 3.857 ops/ms [Average]
  (min, avg, max) = (10.091, 10.238, 10.480), stdev = 0.211
  CI (99.9%): [6.381, 14.095] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.460 ops/ms
# Warmup Iteration   2: 7.636 ops/ms
# Warmup Iteration   3: 8.215 ops/ms
Iteration   1: 8.607 ops/ms
Iteration   2: 8.719 ops/ms
Iteration   3: 8.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.666 ±(99.9%) 1.028 ops/ms [Average]
  (min, avg, max) = (8.607, 8.666, 8.719), stdev = 0.056
  CI (99.9%): [7.639, 9.694] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.935 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.005 ms/op
Iteration   1: 3.238 ±(99.9%) 0.005 ms/op
Iteration   2: 3.271 ±(99.9%) 0.004 ms/op
Iteration   3: 3.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.201 ±(99.9%) 1.735 ms/op [Average]
  (min, avg, max) = (3.092, 3.201, 3.271), stdev = 0.095
  CI (99.9%): [1.466, 4.935] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.034 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.003 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 3.230 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.128 ±(99.9%) 1.672 ms/op [Average]
  (min, avg, max) = (3.053, 3.128, 3.230), stdev = 0.092
  CI (99.9%): [1.456, 4.800] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.005 ms/op
Iteration   1: 3.352 ±(99.9%) 0.006 ms/op
Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
Iteration   3: 3.176 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.206 ±(99.9%) 2.429 ms/op [Average]
  (min, avg, max) = (3.091, 3.206, 3.352), stdev = 0.133
  CI (99.9%): [0.777, 5.635] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.704 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.009 ms/op
Iteration   1: 3.645 ±(99.9%) 0.009 ms/op
Iteration   2: 3.609 ±(99.9%) 0.014 ms/op
Iteration   3: 3.610 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.621 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (3.609, 3.621, 3.645), stdev = 0.020
  CI (99.9%): [3.251, 3.992] (assumes normal distribution)


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
# Warmup Iteration   1: 7.875 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
Iteration   1: 3.323 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  14.365 ms/op
                 createUser·p0.9999: 20.546 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 3.251 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  16.340 ms/op
                 createUser·p0.9999: 24.024 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.306 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  16.569 ms/op
                 createUser·p0.9999: 24.226 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291582
  mean =      3.293 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26120 
    [ 2.500,  5.000) = 259099 
    [ 5.000,  7.500) = 5697 
    [ 7.500, 10.000) = 241 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     16.555 ms/op
     p(99.9900) =     23.822 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 7.296 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 3.367 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  12.575 ms/op
                 existUser·p0.9999: 35.425 ms/op
                 existUser·p1.00:   37.814 ms/op

Iteration   2: 3.279 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  19.468 ms/op
                 existUser·p0.9999: 24.596 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.873 ms/op
                 existUser·p0.9999: 36.594 ms/op
                 existUser·p1.00:   37.552 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298763
  mean =      3.213 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18944 
    [ 2.500,  5.000) = 267416 
    [ 5.000,  7.500) = 11295 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     36.053 ms/op
     p(99.9990) =     37.684 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.741 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.011 ms/op
Iteration   1: 3.161 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  17.190 ms/op
                 getUser·p0.9999: 20.177 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   2: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.762 ms/op
                 getUser·p0.999:  18.329 ms/op
                 getUser·p0.9999: 22.724 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  12.115 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296386
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9036 
    [ 2.500,  5.000) = 281063 
    [ 5.000,  7.500) = 5108 
    [ 7.500, 10.000) = 756 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     18.108 ms/op
     p(99.9900) =     21.737 ms/op
     p(99.9990) =     23.103 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 9.635 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.012 ms/op
Iteration   1: 3.660 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.937 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.121 ms/op
                 listUser·p0.99:   6.398 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.328 ms/op
                 listUser·p0.999:  13.746 ms/op
                 listUser·p0.9999: 22.355 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 3.687 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.112 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 16.204 ms/op
                 listUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257646
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 251180 
    [ 5.000,  7.500) = 4963 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 298 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.637 ms/op
     p(99.9900) =     24.543 ms/op
     p(99.9990) =     25.601 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.872 ± 3.526  ops/ms
ClientPb.existUser                       thrpt       3  10.047 ± 2.715  ops/ms
ClientPb.getUser                         thrpt       3  10.238 ± 3.857  ops/ms
ClientPb.listUser                        thrpt       3   8.666 ± 1.028  ops/ms
ClientPb.createUser                       avgt       3   3.201 ± 1.735   ms/op
ClientPb.existUser                        avgt       3   3.128 ± 1.672   ms/op
ClientPb.getUser                          avgt       3   3.206 ± 2.429   ms/op
ClientPb.listUser                         avgt       3   3.621 ± 0.370   ms/op
ClientPb.createUser                     sample  291582   3.293 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.555           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.822           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.707           ms/op
ClientPb.existUser                      sample  298763   3.213 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.105           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.053           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  296386   3.236 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.057           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.998           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.108           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.737           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.379           ms/op
ClientPb.listUser                       sample  257646   3.725 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.637           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.543           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
